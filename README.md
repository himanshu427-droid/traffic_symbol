# Traffic Symbol Detection

This project implements a basic **CNN-based traffic symbol classification system** using the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset. The objective is to understand the complete workflow of an image classification task using deep learning.

## Overview
- Built a Convolutional Neural Network for traffic symbol classification
- Used the GTSRB dataset for multi-class image classification
- Implemented data loading, preprocessing, training, and testing
- Tested model predictions using a separate script

## Repository Structure
- `gtsrb/` – Full GTSRB dataset
- `gtsrb-small/` – Smaller dataset for quick experimentation
- `traffic.py` – CNN model and training logic
- `test_check.py` – Script for validating model predictions
- `requirements.txt` – Project dependencies

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- OpenCV

## Setup
```bash
pip install -r requirements.txt
python traffic.py
