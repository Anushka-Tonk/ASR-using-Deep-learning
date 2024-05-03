# ASR-using-Deep-learning
Automatic Speech Recognition(ASR) using DeepSpeech2 inspired model
----------
## Overview
This project is a deep learning project inspired by DeepSpeech 2 model which focuses on Automatic Speech Recognition (ASR). The project aims to transcribe audio signals into text using deep learning techniques.

## Table of Contents
-> [Introduction](#introduction)\
-> [Features](#features)\
-> [Installation](#installation)\
-> [Usage](#usage)\
-> [Dataset](#dataset)\
-> [Training](#training)\
-> [Results](#results)\
-> [Contributing](#contributing)\

## Introduction
The project utilizes TensorFlow and deep learning techniques to process audio signals in the form of .wav files and then convert them into text using the deep learning model. It includes components for signal processing, spectrogram generation, model training, and inference.

## Features
- Signal processing using Fourier transforms
- Spectrogram generation using Short Time Fourier Transform (STFT)
- Deep learning model inspired by DeepSpeech 2
- Training pipeline for ASR model
- Inference for real-time speech recognition

## Installation
To install the necessary dependencies, run the following command:

```bash
pip install -r requirements.txt
```

## Usage
To use this ASR system, follow these steps:
1. Preprocess your audio data into spectrograms.
2. Train the deep learning model using the provided training pipeline.
3. Evaluate the model performance using the evaluation pipeline.
4. Use the trained model for real-time speech recognition.

## Dataset
The project uses the LJSpeech dataset.[ To know more about it, check this link.](https://keithito.com/LJ-Speech-Dataset/)

## Training
The deep learning model is trained using the CTC loss function and the Adam optimizer. Training is performed on the spectrogram data generated from the audio recordings.

## Results
The model was trained for 5 epochs using the following configurations:
- Optimizer: Adam
- Learning Rate: 0.001
- Batch Size: 32

The training and validation loss values for each epoch are as follows:

- Epoch 1/5: Training Loss 311.9084, Validation Loss 303.5839
- Epoch 2/5: Training Loss 263.7853, Validation Loss 195.7637
- Epoch 3/5: Training Loss 139.0291, Validation Loss 87.8569
- Epoch 4/5: Training Loss 89.1267, Validation Loss 59.0740
- Epoch 5/5: Training Loss 70.7906, Validation Loss 46.6886

The model demonstrates a significant reduction in loss over the epochs, indicating its ability to learn and generalize well to unseen data.

## Contributing
Contributions to this ASR project are welcome! To contribute, please fork the repository and submit a pull request with your changes.

---
- By Anushka Tonk, contact [anushkaatonk@gmail.com](anushkaatonk@gmail.com)
