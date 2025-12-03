# MSBA 503 Take-Home Assignment – Computer Vision Model Comparison

This project compares two deep learning computer vision models—**YOLOv8** and **Faster R-CNN (ResNet50-FPN)**—on a set of 10 images. The analysis evaluates both models based on:

- Number of objects detected  
- Average detection confidence  
- Inference time  
- Example labels detected  

In addition, the project extracts simple non–deep-learning image features such as resolution, aspect ratio, average RGB color values, and edge density.

---

## Project Structure
├── images/ # (Not included in repo) Add your 10 images here before running
├── TakeHome.ipynb # Jupyter Notebook with code and printed outputs
├── results.csv # Automatically generated results table
├── requirements.txt # Python dependencies
└── README.md # Documentation

*Images are intentionally not uploaded to GitHub to follow assignment instructions.*

---

## Setup

Install the required dependencies:

pip install -r requirements.txt
Running the Notebook

Place your 10 images inside the images/ folder.

Open the notebook:

jupyter notebook TakeHome.ipynb


Run all cells.
The notebook will run both models, extract metrics, and save a combined results table to results.csv.

Running the Notebook

Place your 10 images inside the images/ folder.

Open the notebook:

jupyter notebook TakeHome.ipynb


Run all cells.
The notebook will run both models, extract metrics, and save a combined results table to results.csv.

Output Details

Each row in results.csv includes:

image – file name

model – YOLOv8 or Faster R-CNN

num_objects – number of detections

mean_confidence – average detection probability

labels – detected classes

time_sec – inference time

width, height, aspect_ratio – image size features

mean_R, mean_G, mean_B – average color channels

edge_density – percentage of edge pixels

These fields were used to build the comparison table included in the written report.

Notes

This repository supports:

Part A: Model comparison + additional features

Part B: Public GitHub link, documented code, and reproducibility

Acknowledgment

This project was completed for the MSBA 503: Foundations of Business Analytics take-home assignment.
