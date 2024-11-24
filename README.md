# Pothole Detection and Classification

This project aims to develop a computer vision model to automatically detect and classify road images as either having potholes or being in normal condition, contributing to improved road safety and maintenance management.

## Project Overview

The model is trained to detect and classify images of roads into two categories:
- **Normal**: Images of smooth roads.
- **Potholes**: Images of roads with potholes.

### Dataset

The dataset used consists of two categories:
- **Normal**: 352 images of smooth roads taken from various angles.
- **Potholes**: 329 images of roads with potholes.

The dataset is located in the following directories:
- `Normal`: `/path/to/dataset/Normal`
- `Potholes`: `/path/to/dataset/Potholes`

### Technologies Used
- Python
- OpenCV
- TensorFlow/Keras (Deep Learning Framework)
- ResNet50 (Pretrained backbone)