# Classification and Captioning Aircraft Damage Using Pretrained Models Overview
The goal of this project is to develop an automated model that accurately classifies aircraft damage from images. By the end of the project, you will have trained and evaluated a model that utilizes feature extraction from VGG16 for damage classification. This model will be applicable in real-world damage detection within the aviation industry. Furthermore, the project will showcase how we can use a Transformer-based model to caption and summarize images, providing a detailed description of the damage.

- A trained model capable of classifying aircraft images into "dent" and "crack" categories, enabling automated aircraft damage detection.
- A Transformer-based model that generates captions and summaries of images

## Files
You will be using the [Aircraft dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/ZjXM4RKxlBK9__ZjHBLl5A/aircraft-damage-dataset-v1.tar).
The dataset is taken from the here (Original Source): [Roboflow Aircraft Dataset](https://universe.roboflow.com/youssef-donia-fhktl/aircraft-damage-detection-1j9qk) Provided by a Roboflow user, License: CC BY 4.

## Installation
- pip install pandas 2.2.3
- pip install tensorflow 2.17.1
- pip install pillow 11.1.0
- pip install matplotlib 3.9.2
- pip install transformers 4.38.2
- pip install torch

- import zipfile
- import keras

  from keras.models import Sequential, Model

  from keras.layers import Dense, Dropout, Flatten

  from keras.applications import VGG16

  from keras.optimizers import Adam

- import tensorflow as tf

  from tensorflow.keras.preprocessing.image import ImageDataGenerator

- import matplotlib.pyplot as plt
- import numpy as np

  from keras.preprocessing import image

- import random
