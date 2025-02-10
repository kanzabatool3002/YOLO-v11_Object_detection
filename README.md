# YOLOv11 Training on Custom Dataset

This repository provides instructions for training YOLOv11 on a custom dataset using Roboflow. YOLOv11 (You Only Look Once version 11) is a state-of-the-art deep learning model for real-time object detection. In this project, we train YOLOv11 to detect various objects from a custom dataset.

## Dataset Classes

The dataset contains the following classes:

- **Gun**
- **Knife**
- **Human**
- **Bus**
- **Car**
- **Truck**
- **Bike**
- **Highroof**
- **Rickshaw**

## Prerequisites

- Python 3.x
- Google Colab (recommended for ease of use)
- Roboflow account and API key
- YOLOv11 repository for training the model

## Getting Started

1. **Open the Colab Notebook**:  
   To get started, open the Colab notebook by clicking the badge below. It contains all the necessary steps to set up the environment and train the model.

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kanzabatool3002/YOLO-v11_Object_detection/refs/heads/main/Train_yolo_v11_Object_Detection_on_Custom_dataset.ipynb)

2. **Roboflow Dataset**:  
   The dataset used in this project is hosted on Roboflow. To access it, sign up for a free account on Roboflow, generate an API key, and use it to download the dataset into your training environment.

   You can explore and access the dataset here:  
   [**Safer Sight Dataset on Roboflow**](https://universe.roboflow.com/object-detection-dua2n/safer-sight)

3. **Training the Model**:  
   Once you have the dataset, follow the instructions in the notebook to train YOLOv11 on your custom dataset. You'll find detailed steps for setting up the training environment, including installing the necessary libraries and configuring the training process.

4. **Evaluate and Test**:  
   After training the model, you can test its performance on new images or video to check the accuracy and precision of the object detection.

## Benefits of Using Roboflow

- **Easy Dataset Management**: Roboflow makes it easy to manage and preprocess your dataset.
- **Pre-built Integrations**: The platform integrates seamlessly with popular object detection frameworks like YOLO, making it easier to train models.
- **Access to Versioned Datasets**: Roboflow provides versioned datasets, allowing you to track changes and improvements over time.
