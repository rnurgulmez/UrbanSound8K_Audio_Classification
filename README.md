# UrbanSound8K Sound Classification

This repository contains the code for classifying urban sounds using machine learning techniques with the UrbanSound8K dataset.

## Introduction

The UrbanSound8K dataset consists of 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes, including air_conditioner, car_horn, children_playing, dog_bark, drilling, engine_idling, gun_shot, jackhammer, siren, and street_music.

## What's Done in This Project

In this project, the following steps are performed:

1. **Data Preprocessing:** The audio files are loaded and preprocessed using Librosa library to extract features such as MFCCs (Mel-frequency cepstral coefficients).

2. **Feature Extraction:** MFCC features are extracted from the audio files. These features capture the characteristics of the audio signals and are used as inputs to the machine learning model.

3. **Model Training:** A deep learning model is built using TensorFlow and Keras to classify the audio files into their respective classes. The model architecture consists of multiple dense layers with activation functions and dropout layers to prevent overfitting.

4. **Model Evaluation:** The model is trained on a training dataset and evaluated on a separate test dataset to measure its performance. The accuracy of the model on the test set is computed to assess its effectiveness in classifying urban sounds.

5. **Prediction:** The trained model can also be used to predict the class of new audio files. The `predict_sound.py` script allows users to input a sound file and get the predicted class label.

## Requirements

To run this project, you need the following libraries:

- TensorFlow
- Matplotlib
- Pandas
- Librosa
- NumPy
- tqd

dataset : https://urbansounddataset.weebly.com/urbansound8k.html
