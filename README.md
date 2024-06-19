# Cornache Machine Learning

This project provides tools for loading an image dataset, performing random oversampling on the minority class, and displaying the sample counts before and after oversampling.

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

Cornache Machine Learning is a project aimed at simplifying the process of working with imbalanced image datasets. It includes tools for loading image datasets, performing oversampling on minority classes, and visualizing the class distribution before and after oversampling.

## Datasets

This project use 4 Classes in total:
1. Blight
2. Common_Rusht
3.  Gray_Leaf_Spot
4.  Healty

Merge Dataset Download Link [Here](https://github.com/cornacheteam2024/Cornache-Machine_Learning/tree/main/dataset)

## Features

- Load an image dataset from a specified directory.
- Perform random oversampling on a specified minority class by rotating images.
- Display the count of samples per class before and after oversampling.

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
