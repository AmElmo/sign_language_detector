# 🤔 Problem

70 millions people in the world are considered functionally deaf.
The vast majority of health practicioners do not speak sign languages. Communications with deaf patients is a struggle.


# 💡 Solution

Sign language detector for medical practitioner to help them understand symptoms from hearing-impaired patients.
Our model is trained on the most common symptoms that doctors and nurses may face on a daily basis.

We use American Sign Language (ASL) for this project but the code can be reused to train on any form of sign language.


# 🤖 Stack overview


Open CV: to work easily with our webcam to generat our dataset
Mediapipe: Google library to extract keypoints from a human body in real time
Tensorflow: for building and training our models
Tensorflow JS: for converting to layer model or graph model and use in a JavaScript application
Numpy: classic for dealing with data extraction and pre-processing


# 🪜 Project steps

## 1. 💽 Data collection

We first considered a large-scale dataset for Word-Level American Sign Language: https://github.com/dxli94/WLASL - but since we used a reduced scope of 9 words to translate for this project, we generated our own dataset with our own videos.

!!! Describe number of videos per words + nb of frames

## 2. Training an LSTM neural network

## 2. Training a CNN + LSTM neural network



## 3. Evaluation and test in real time

We logged metrics from our model and displayed them in Tensorboard.


## 4. Convert model to Tensorflow JS

Depending on the type of model built, we converted our .h5 Keras model to a layers model or graph model.

LSTM 👉 layers model
CNN + LSTM 👉 graph model
