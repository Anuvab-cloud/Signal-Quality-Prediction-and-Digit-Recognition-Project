# Signal-Quality-Prediction-and-Digit-Recognition-Project

## Overview

This project involves two separate parts:

### **Part A: Signal Quality Prediction**
The goal of this part is to build a machine learning model that predicts the signal quality of communication equipment using various signal parameters. The company aims to optimize their product's performance by understanding and predicting signal strength based on data inputs.

### **Part B: Multi-Digit Number Recognition (SVHN Dataset)**
The second part focuses on recognizing multi-digit numbers in images captured at street level, specifically using the **SVHN (Street View House Numbers)** dataset. This task involves optical character recognition (OCR) on natural scene images, which presents a complex challenge due to environmental and image acquisition factors.

## Objectives

- **Part A**: Build a machine learning classifier to predict the signal quality using a dataset of signal parameters.
- **Part B**: Develop a digit classifier using the SVHN dataset to recognize multi-digit numbers in street-level images.

## Dataset

### **Part A: Signal Quality Prediction**
The dataset for this part contains signal test results with the following columns:
- **Parameters**: Various measurable signal parameters.
- **Signal_Quality**: Final signal strength or quality.

### **Part B: SVHN Dataset**
The SVHN dataset is composed of images of house numbers captured from Google Street View imagery. It presents a more complex problem than simpler datasets like MNIST due to distractors and real-world challenges, such as different fonts, lighting, and occlusions.

### Dataset Format:
The SVHN dataset is available in **h5py file format**. Each image is labeled with the prominent digit visible in the image.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Signal-QC-and-SVHN-Digit-Classifier.git
