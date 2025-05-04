# Hand Action Recognition (Sign Language Recognition)

This project focuses on the development of a real-time hand gesture recognition system to support accessibility tools. The model utilizes Long Short-Term Memory (LSTM) networks to recognize hand gestures, achieving an accuracy of 93% on 5 custom hand gestures. This system can be integrated into applications to provide real-time sign language recognition, enabling improved accessibility for individuals with hearing impairments.

## Features

- **Gesture Recognition:** Recognizes 4 custom hand gestures in real time.
- **High Accuracy:** Achieved 93% accuracy on the recognition of hand gestures.
- **Real-time Processing:** The system is optimized for real-time gesture recognition with sub-second response times.
- **Accessibility Tool:** Can be integrated into applications to assist people with hearing impairments by recognizing sign language gestures.

## Technologies Used

- **TensorFlow:** For building and training the neural network models.
- **Mediapipe:** For hand tracking and gesture extraction.
- **OpenCV:** For video processing and frame handling.
- **Keras:** Used as a high-level API for building the LSTM-based model.
- **LSTM (Long Short-Term Memory):** Recurrent neural network used for gesture sequence recognition.

## Model Overview

The project employs an LSTM-based model for gesture recognition. LSTMs are particularly well-suited for time-series and sequence data, making them ideal for recognizing gestures in hand movements, where temporal dependencies are crucial.

The model is trained on a dataset of 4 custom hand gestures, each representing different signs. The model is capable of distinguishing between these gestures and providing real-time feedback for accessibility purposes.

## Setup Instructions

### Requirements

- Python 3.x
- TensorFlow
- OpenCV
- Mediapipe
- Keras
