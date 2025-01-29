# Street View Image Classification for Turkish Cities

## Challenge Overview

This project involves developing a machine learning model to classify street view images into three major cities in Turkey:

Istanbul: The transcontinental metropolis bridging Europe and Asia.

Ankara: The modern capital city.

Izmir: The pearl of the Aegean Sea.

## Objective

The goal of this challenge is to build a deep learning model that can accurately identify which city a given street view image belongs to. This task requires analyzing and recognizing distinctive architectural styles, urban planning characteristics, and geographical features unique to each city.

## Dataset

The dataset consists of labeled street view images of Istanbul, Ankara, and Izmir. The dataset includes:

Training images located in /kaggle/input/datathon-ai-qualification-round/train/train

Test images located in /kaggle/input/datathon-ai-qualification-round/test/test

CSV file containing image filenames and their corresponding city labels (train_data.csv)

Dataset: https://www.kaggle.com/competitions/datathon-ai-qualification-round/data

## Model Architecture

A Convolutional Neural Network (CNN) is used for classification. The architecture includes:

Multiple convolutional layers with batch normalization and ReLU activation.

Max pooling layers for dimensionality reduction.

A fully connected dense layer with dropout for regularization.

Softmax activation for multi-class classification.

## Result
The model achieved an F1 score of 81
