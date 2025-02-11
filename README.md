# Tomato Plant Stage Detection using Deep Learning Models

## Description
This project utilizes various deep learning models to detect the first two stages of tomato plant leaves. The custom dataset used for training contains images of tomato plant leaves at **Stage 1** and **Stage 2** of growth. The following models were used for this task:

- **Custom CNN**
- **ResNet50**
- **InceptionV3**
- **EfficientNetB0**
- **YOLOv3**
- **VGG16**

The dataset used for this project was collected from the fields of **Tamil Nadu Agricultural University (TNAU), Coimbatore**. The models aim to accurately classify the plant leaves into their respective growth stages to aid in early-stage detection and plant health monitoring.

## Colab Notebook Link
You can access the Google Colab notebook by clicking the link below:

[Open the Colab Notebook](https://colab.research.google.com/drive/1tmqL-NQIChPi46JRX0bcSZf0Z4O6JCcb)

## How to Use
1. Open the Colab notebook using the link above.
2. Ensure that all the required dependencies (listed below) are installed.
3. Run the code cells to perform model training and evaluation.
4. Follow the notebook's instructions to visualize the results and test the models on your custom dataset.
## Dataset
The dataset used in this project is a custom dataset consisting of images of tomato plant leaves at Stage 1 and Stage 2. The dataset was collected from the fields of Tamil Nadu Agricultural University (TNAU), Coimbatore.

## Dataset Details:
Stage 1: Images of tomato leaves in the early stage of growth.
Stage 2: Images of tomato leaves in the mid-stage of growth.
The dataset contains labeled images with the two stages, which were used to train the models for plant stage detection.
The dataset can be split into training and testing sets for model evaluation, and all images were preprocessed for use with the deep learning models.

## Requirements
To run the notebook locally or in your environment, make sure you have the following dependencies installed:

- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Pandas

You can install the necessary libraries using the following command:

```bash
pip install tensorflow keras opencv-python numpy matplotlib pandas
