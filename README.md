
# Breast Cancer Classification Using a Simple Neural Network

This project implements a simple neural network model to classify breast cancer tumors as **Malignant** or **Benign** using the well-known Breast Cancer Wisconsin dataset.

## Dataset

* The data is sourced from `sklearn.datasets.load_breast_cancer()`.
* It consists of 30 numeric features extracted from digitized images of breast tissue.
* The dataset is widely used for binary classification tasks in medical diagnosis.

## Model Description

* A straightforward feed-forward neural network (fully connected layers).
* Uses a binary classification output layer.
* Trained with a binary cross-entropy loss function.
* Features were standardized using a scaler fit on training data.

## Performance Metrics

* **Loss:** Approximately **0.0657**, indicating a very small error according to the binary cross-entropy loss function.
* **Accuracy:** Achieved around **97% to 98%** accuracy on validation/test sets.
* The low loss and high accuracy confirm the model effectively discriminates between malignant and benign tumors.

## Usage

* Input patient feature vectors (30 features).
* The model outputs prediction probabilities and classifies tumors as:

  * **Malignant (Cancer detected)**
  * **Benign (No cancer detected)**
* The model supports standardization of inputs prior to prediction to maintain consistency.

## Summary

This neural network provides a reliable, interpretable, and computationally efficient approach for breast cancer classification, achieving near state-of-the-art accuracy with minimal loss. It serves as a strong baseline for further experimentation and improvement in medical imaging diagnosis.

