# Implementation for CS231n: Deep Learning for Computer Vision

## Overview
- Homepage: [https://cs231n.stanford.edu/schedule.html](https://cs231n.stanford.edu/schedule.html)
- Labs:
    + Assignment1: Image Classification, kNN, SVM, Softmax, Fully-Connected Neural Network
    + Assignment2: Fully-Connected Nets, Batch Normalization, Dropout, Convolutional Nets, Network Visualization
    + Assignment3: Image Captioning with Vanilla RNNs, LSTMs, Transformers, Generative Adversarial Networks

## Setup
1. Download Dataset: run scripts under assignment/cs231n/datasets, leave data in "datasets" dir.
2. Environment Setup: run "pip install -r requirements.txt"

## Run 
If you want to run it locally instead of running on Google Colab, just ignore code block like following.
```
from google.colab import drive

drive.mount('/content/drive')

# TODO: Enter the path in your Drive of the assignment.
# e.g. 'cs231n/assignments/assignment1/'
FOLDERNAME = None

assert FOLDERNAME is not None, "[!] Enter the foldername."
```