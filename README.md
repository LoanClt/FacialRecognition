# Face Recognition with CNN and Eigenfaces

This repository contains Python scripts for face recognition using two different approaches:
1. **Convolutional Neural Networks (CNN)**: A deep learning approach for facial recognition.
2. **Eigenfaces with PCA and k-NN**: A traditional machine learning approach using Principal Component Analysis (PCA) and k-Nearest Neighbors (k-NN).

## Features
- **Image Preprocessing**: Grayscale conversion, resizing, and normalization.
- **Data Augmentation**: Increases dataset size using transformations like flipping, brightness adjustment, noise addition, rotation, and blurring.
- **CNN Model**: Built using TensorFlow/Keras with convolutional and dense layers.
- **Eigenface Recognizer**: Uses PCA for dimensionality reduction and k-NN for classification.
- **Evaluation Metrics**: Includes accuracy calculation, confusion matrix, and visualization of predictions.
- **Visualization Tools**: Displays eigenfaces, test results, and model performance.

## Installation
```sh
pip install -r requirements.txt
```

## Usage
## CNN Model
Run the script to train a CNN model on the dataset:
```sh
python cnn_face_recognition.py
```

## Eigenface Recognizer
Run the script to train a CNN model on the dataset:
```sh
python eigenface_recognition.py
```

## Dataset Structure
```sh
Dataset/
    ├── subject1/
    │   ├── img1.jpg
    │   ├── img2.jpg
    ├── subject2/
    │   ├── img1.jpg
    │   ├── img2.jpg
```




Matthew Turk, Alex Pentland; Eigenfaces for Recognition. J Cogn Neurosci 1991; 3 (1): 71–86. doi: https://doi.org/10.1162/jocn.1991.3.1.71


## Authors

- [@LoanClt](https://www.github.com/https://github.com/LoanClt)


## Running Tests

TODO


## Feedback

If you have any feedback, please reach out to us at loan.challeat@institutoptique.fr

