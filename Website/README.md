# Speech Command Recognition with CNNs

This website presents our ECE465 Machine Learning project on speech command recognition using convolutional neural networks.

## Project Overview

The project classifies short spoken commands by converting audio clips into mel spectrogram images and passing them through a CNN. The final system recognizes the commands `go`, `no`, `stop`, and `yes`, while also handling `silence` and uncertain inputs using an `unknown` class.

## Key Features

- MATLAB implementation
- Google Speech Commands v0.02 dataset
- Mel spectrogram preprocessing
- 64×64 image-based CNN inputs
- Three-layer CNN architecture
- Batch normalization, max pooling, and dropout
- Noise augmentation and random gain/time-shift augmentation
- Real-time MATLAB audio demo
- Confidence thresholding for unknown inputs

## Website Files

Main page:

```text
index.html

Images should be placed in:

static/images/

PDFs should be placed in:

static/pdfs/

CSS and JavaScript files are located in:

static/css/
static/js/
How to View the Website

Open index.html in a web browser.

For best results, keep the folder structure unchanged so that all image, PDF, CSS, and JavaScript links work correctly.

Authors

Benjamin Bellenchia, Brian Patterson, Eric Dutan, and Kai Perez
UAlbany CNSE ECE465 - Machine Learning Project
Showcase Day 2026
