# HumanActionRecognition
Human action recognition model using CNN + LSTM convolutional network
# Human Action Recognition

This repository contains code for human action recognition using deep learning models.

## Introduction

The human action recognition model included in this repository is based on a Long Short-Term Memory (LSTM) neural network architecture. It is trained to classify various human actions from video data. The model takes sequential frames of a video as input and predicts the action performed in the video.

## Model Details

The LSTM model architecture consists of multiple LSTM layers followed by fully connected layers. It was trained on a dataset comprising several action categories, including archery, biking, horse riding, walking with a dog, body weight squats, bowling, boxing (punching bag), diving, drumming, and golf swing.

## Usage

To use the model for action recognition:
- Upload a video file or an image.
- Utilize the provided Python script `action_recognition.py`.
- Follow the instructions provided in the script to predict actions in videos or images.

## Requirements

To run the code, you need the following dependencies:
- Python 3
- OpenCV
- TensorFlow/Keras

## Contribution

Feel free to contribute to this repository by adding improvements or expanding the dataset for better model performance. Pull requests are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
