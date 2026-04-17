# Pneumonia Detection using CNN: mad2502-project

## Overview
This project applies convolutional neural networks (CNN) to classify chest X-rays as either Normal or Pneumonia. The goal is to evaluate how effective machine learning can be in assisting medical diagnosis. 
This project was completed for MAD2502 and focuses on predictive modeling, classification, and image-based deep learning.

## Authors
Michael Genzone
Abigail Laber

## Dataset
We used the Chest X-Ray Pneumonia dataset from Kaggle:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download

## Setup Instructions
1. Download the dataset
2. Extract the dataset into your project folder
3. Make sure the path in the code matches:
BASE_DIR = "archive/chest_xray/chest_xray"
4. Install the following Python libraries before running: numpy, pandas, tensorflow, scikit-learn, matplotlib

## How to Run
1. Open pneumonia_project.ipynb
2. Run all cells in order
3. The model will load and preprocess data, train the CNN, and evaluate performance on the test set

## Results
The model achieved
Accuracy: 81.57%
Precision: 77.78%
Recall: 98.72 %
This indicates the model is highly effective at detecting pneumonia cases (high recall), which is especially important in a medical setting. 

