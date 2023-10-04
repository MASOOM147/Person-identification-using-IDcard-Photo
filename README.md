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
- [Contact](#contact)

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

   
    pip install -r requirements.txt

## Usage
You can simply Download the notebook and edit paths and photos according to your directories or
You can use this code to perform person identity detection and verification. Modify the input images, adjust the similarity threshold, and experiment with different use cases. Here's an example of how to use the code:

     
         # Example usage code snippet
         import cv2
         
         # Load and compare two images
         image1 = cv2.imread('image1.jpg')
         image2 = cv2.imread('image2.jpg')
         result = compare(image1, image2)
         
         # Print the result
         if result:
             print("The faces are a match!")
         else:
             print("The faces are not a match.")

## Evaluation
The provided code includes an evaluation section where you can test the model's performance on sample image pairs. Results are visualized using a confusion matrix.

## Contributing

Contributions are welcome! If you'd like to contribute to this repository, here's how:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Open a pull request with a detailed description of your changes.

Please make sure to follow the project's code of conduct and guidelines when contributing.

## Contact

If you have any questions, suggestions, or just want to connect, you can reach me at [mmasoomedu1@gmail.com]. You can also find me on GitHub as [MASOOM147](https://github.com/MASOOM147).
