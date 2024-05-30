## Members

Anuj Rayamajhi, Nishant Uprety

## Face Classification with ResNet-18 on LFW Dataset

This project aims to develop a face classification model using the LFW (Labeled Faces in the Wild) dataset. We will train a ResNet-18 model on both uncropped and cropped face images, comparing the performance of these models. The cropping of faces is done using MTCNN (Multi-task Cascaded Convolutional Networks).

## Dataset

The dataset is sampled from the LFW face dataset:

- **Total number of images:** 9,164
- **Total number of classes:** 1,680

## Project Workflow

### Data Preparation

1. Download and preprocess the LFW dataset.
2. Crop faces from images using MTCNN.

### Model Training

1. Train a ResNet-18 model on uncropped face images.
2. Train another ResNet-18 model on cropped face images.

### Model Evaluation

1. Benchmark the performance of both models.
2. Compare accuracy, precision, recall, and F1-score.

## Requirements

- Python 3.7+
- PyTorch
- torchvision
- MTCNN
- numpy
- pandas
- scikit-learn

## Installation

Clone the repository and install the required packages:

```sh
git clone https://github.com/yourusername/face-classification-resnet18.git
cd face-classification-resnet18
pip install -r requirements.txt
