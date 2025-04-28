# Emotion Detection Project

This repository contains an emotion detection project. The project includes Jupyter Notebooks and a pre-trained model for analyzing emotions.

## Overview

We have developed an emotion classification model based on a CNN-BiLSTM architecture.
The primary focus of the project was to design a lightweight model capable of running on devices with limited computational resources.
We have largely succeeded in this goal — the final trained model is less than 5 MB in size without significant compromise on accuracy or performance.

## Files

- `EmotionRecognition.ipynb`: A Jupyter Notebook for emotion detection.
- `emotion_detection_model.h5`: A pre-trained model for emotion detection.

## How to Use

1. Clone the repository.
2. Extract the `emotion_detection_model.zip` file.
3. Now you can start training.
4. Training Information
   The model was trained using Kaggle's remote GPU server for faster computation.
   If you wish to retrain the model, ensure that your system has at least 14 GB of GPU memory to handle the training workload efficiently.
   You are free to train on any environment, but the hardware requirements must be met for optimal performance.
5. Open the Jupyter Notebooks to explore or run the emotion detection analysis.

## License

This project is licensed under the Creative Commons Zero v1.0 Universal License.
