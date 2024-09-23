# ML-With-Milad

Welcome to the **ML-With-Milad** repository! This repository serves as a collection of my machine learning projects, showcasing various modeling techniques, data preprocessing steps, and evaluation metrics applied to different datasets.

## Project Overview

### 1. **Pedestrian Finder** - [PedestrianFinder.ipynb](./PedestrianFinder.ipynb)
This project focuses on pedestrian detection using a pre-trained **Mask R-CNN** model, fine-tuned on the **PennFudan Pedestrian Dataset**.

#### Key Features:
- **Object Detection**: Locating pedestrians in images by drawing bounding boxes.
- **Instance Segmentation**: Creating pixel-perfect segmentation masks around each detected pedestrian.
- **Data Augmentation**: Enhances model performance with techniques such as resizing and random horizontal flipping.
- **Model Performance**: Evaluated using standard metrics like **Average Precision (AP)** and **Intersection over Union (IoU)**.

The notebook demonstrates:
- Loading a pre-trained **Mask R-CNN** model.
- Fine-tuning the model on custom data (PennFudan Pedestrian dataset).
- Training the model and visualizing results (bounding boxes and masks).
