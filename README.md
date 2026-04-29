# Website Link:

https://Eric-Dutan.github.io/ML_Project/

# Speech Command and Speaker Recognition

ECE465 Machine Learning project using MATLAB to recognize spoken commands and identify the speaker for the command **"go"**.

## Overview

This project uses a two-stage voice recognition pipeline:

1. A **CNN** classifies short speech clips as `go`, `no`, `stop`, `yes`, `silence`, or `unknown`.
2. If the CNN detects the word `go`, a **GMM speaker recognition model** uses MFCC features to predict which team member spoke.

The goal is to build a simple voice-command system that can reject uncertain inputs and demonstrate speaker identification.

## Main Features

- MATLAB implementation
- Google Speech Commands dataset
- Mel spectrogram preprocessing for CNN input
- CNN command classification
- Silence and unknown-input handling
- Confidence thresholding for uncertain predictions
- MFCC feature extraction for speaker recognition
- GMM-based speaker identification for the word `go`
- Real-time MATLAB recording demo

## Repository Structure

Data Set/                Dataset files
Website/                 Project website files
model_CNN/               CNN training and command-recognition model files
model_SVM/               Earlier SVM model files
voice_recognition_GMM/   GMM speaker-recognition files
ML_Project_Demo.mlx      Main MATLAB live demo
README.md                Project summary

## Website

Open the website from:

Website/index.html

Website assets are stored in:

Website/static/images/
Website/static/pdfs/
Website/static/css/
Website/static/js/

## Demo

The main demo records a short audio clip, predicts the spoken command using the CNN, and then runs speaker recognition only when the command is predicted as `go`.

## Authors

Benjamin Bellenchia, Brian Patterson, Eric Dutan, and Kai Perez  
UAlbany CNSE ECE465 Machine Learning Project  
Showcase Day 2026
