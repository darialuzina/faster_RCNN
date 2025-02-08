# Faster R-CNN for Object Detection

## Overview

Implementing **Faster R-CNN** for object detection using **PyTorch** and **Torchvision**. The model is trained on the **Pascal VOC** dataset and fine-tuned for improved detection accuracy. The notebook includes data preprocessing, model training, evaluation, and visualization of detected objects.

## Features

- Uses **Faster R-CNN with MobileNetV3 backbone** for object detection.
- Trained on the **Pascal VOC dataset**.
- Implements data transformations and custom target formatting.
- Supports **Non-Maximum Suppression (NMS)** for filtering overlapping predictions.
- Computes **Mean Average Precision (mAP)** for model evaluation.
- Visualizes **ground truth vs. predicted bounding boxes**.
