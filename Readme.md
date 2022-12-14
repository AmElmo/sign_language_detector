# 🤔 Problem

70 millions people in the world are considered functionally deaf.
The vast majority of health practicioners do not speak sign languages. Communications with deaf patients is a struggle.


# 💡 Solution

Sign language detector for medical practitioner to help them understand symptoms from hearing-impaired patients.
Our model is trained on the most common symptoms that doctors and nurses face on a daily basis.

We use American Sign Language (ASL) for this project but it can be reused to train on any form of sign language.


# 🤖 Stack overview

Tensorflow

Open CV: to work easily with our webcam
Mediapipe: to extract keypoints from a human body in real time



# 🪜 Project steps

## 1. 💽 Data collection

We first considered a large-scale dataset for Word-Level American Sign Language: https://github.com/dxli94/WLASL - but since we used a reduced scope of 9 words to translate for this project, we generated our own dataset with our own videos.

!!! Describe number of videos per words + nb of frames

## 2. Training the LSTM neural network


## 3. Evaluation and test in real time


## 4. Convert model to Tensorflow JS
