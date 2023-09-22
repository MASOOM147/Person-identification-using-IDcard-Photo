# Person-identification-using-IDcard-Photo

![Python Version](https://img.shields.io/badge/Python-3.7%20%7C%203.8%20%7C%203.9-blue)


Welcome to the "Person Identity Detection Model" repository. This project demonstrates person identity verification using a Haar Cascade classifier for face detection and face_recognition to compare and recognise face. It leverages GPU acceleration for efficient and accurate image processing and comparison Although you also can use CPU and run this Notebook.

## Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In today's digital age, person identity detection and verification have become essential in various applications, from security systems to user authentication. This repository showcases a Python code snippet that utilizes a Haar Cascade classifier and face_recognition to perform these tasks effectively.

## Key Features

- **Libraries and Dependencies:** We provide instructions for installing and importing essential libraries, such as `dlib`, `numpy`, `matplotlib`, `opencv-python`, and `face_recognition`.
- **Face Detection and Feature Extraction:** The code employs a Haar Cascade classifier for face detection and a pre-trained shape predictor model for locating facial landmarks.
- **Face Comparison:** You can use this code to compare two input images and determine if they belong to the same person. It extracts facial features, calculates similarity, and applies a predefined threshold for identity verification.
- **Eye Distance Calculation:** Additionally, the repository includes a function to calculate the distance between the eyes in a given image.
- **Evaluation and Visualization:** The code evaluates multiple pairs of face and ID card images, predicting whether they belong to the same person. The results are presented in a confusion matrix, providing insights into the model's performance.

## Installation

To get started with this project, follow these installation steps:

1. Clone this repository to your local machine using:

   ```shell
   git clone https://github.com/MASOOM147/Person-identification-using-IDcard-Photo.git

## Install r requirements:
 Install the required Python libraries using pip:

  ```shell
  pip install -r requirements.txt
