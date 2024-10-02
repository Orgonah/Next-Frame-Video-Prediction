# Next-Frame-Video-Prediction

This repository contains a Convolutional LSTM model for next-frame video prediction using the Moving MNIST dataset.

## Introduction

This project demonstrates how to build and train a Convolutional LSTM model for predicting the next frame in a video sequence.

## Model

A Convolutional LSTM model is constructed using Keras, designed to handle sequences of video frames and predict the next frame.

## Training

The model is trained using the Moving MNIST dataset, which provides sequences of handwritten digits in motion. The training involves:

1. Preparing the dataset by normalizing and reshaping the frames.
2. Shifting frames to create input-output pairs for prediction.
3. Training the model with early stopping and learning rate reduction.

## Usage

Load and preprocess the Moving MNIST dataset.
Train the Convolutional LSTM model.
Predict the next frames in a sequence and visualize the results.
