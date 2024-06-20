# Cornache Machine Learning

This repository contains the Corn Leaf Disease Classification Model, datasets, and the associated Jupyter notebook. The datasets consist of 4,800 images categorized into 4 classes. The model achieved an accuracy of 90%.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
  - [Local Environment Setup](#local-environment-setup)
- [Usage](#usage)
- [Authors](#authors)

## Introduction

Cornache Machine Learning is a project dedicated to developing a model for detecting corn leaf diseases. The project includes tools for loading image datasets, performing oversampling on minority classes, and visualizing the class distribution before and after oversampling. The model is trained using a Convolutional Neural Network (CNN) architecture and evaluated with K-Fold Cross Validation. TensorFlow and Keras libraries are utilized for training, with the F1-score serving as the accuracy metric. This project successfully developed a model that can detect corn leaf diseases with an F1-score of 90% and a high confidence level.

## Datasets

This project use 4 Classes in total and Datasets consist of 4800 images with 1200 images for each class, The classes are:
1. Blight
2. Common_Rusht
3. Gray_Leaf_Spot
4. Healty

Merge Dataset Download Link [Here](https://github.com/cornacheteam2024/Cornache-Machine_Learning/tree/main/dataset)

## Features

- Load an image dataset from a specified directory.
- Perform random oversampling on a specified minority class with augmentation by rotating images.
- Display the count of samples per class before and after oversampling.
- Build and train model with TensorFlow
- Evaluation model with K-Fold Cross Validation
- Using F1-Score and Confusion Matrix as accuracy metrics

## Requirements

- TensorFlow
- Python
- Google Colab
- Kaggle
- Matplotlib
- Keras
- Numpy
- Pandas
- Seaborn
- OpenCV2
- scikit-learn
- PIL (Pillow)

## Installation

### Local Environment Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/cornacheteam2024/Cornache-Machine_Learning.git
   cd Cornache-Machine_Learning
   ```

2. (Optional) Set up a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install tensorflow opencv-python-headless numpy scikit-learn pillow matplotlib keras pandas seaborn
   ```

## Usage

1. Run the preprocessing notebook:

   ```bash
   jupyter notebook Preprocessing.ipynb
   ```

2. Build the model:

   ```bash
   jupyter notebook Building_Model.ipynb
   ```

## Authors

- [@marisa-nao](https://github.com/marisa-nao)
- [@ahmadtaufiqramadhan](https://github.com/ahmadtaufiqramadhan)
- [@revano17](https://github.com/revano17)

---

For more details, visit the [repository](https://github.com/cornacheteam2024/Cornache-Machine_Learning).
