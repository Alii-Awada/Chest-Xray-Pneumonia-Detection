# Pneumonia Detection from Chest X-Ray Images

## Project Overview
This project uses Deep Learning and Convolutional Neural Networks (CNN) to classify chest X-ray images into two categories:

- NORMAL
- PNEUMONIA

The goal is to demonstrate how deep learning can be used for medical image classification.

## Dataset
**Chest X-Ray Images (Pneumonia)**

Source: [Kaggle Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

The dataset contains approximately 5,863 images across training, validation, and testing folders.

## Technologies Used
- Python
- TensorFlow / Keras
- CNN
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub
- Google Colab

## Project Workflow
1. Data collection
2. Exploratory data analysis
3. Image preprocessing
4. Data augmentation
5. CNN model development
6. Model training
7. Model evaluation
8. Prediction on new X-ray images

## Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training and validation curves

## Dataset Download

The dataset can be downloaded using KaggleHub:

```python
!pip install kagglehub

import kagglehub

path = kagglehub.dataset_download(
    "paultimothymooney/chest-xray-pneumonia"
)
```

## How to Run
1. Clone or download this repository.
2. Open `Pneumonia_Detection.ipynb` in Google Colab.
3. Run the notebook cells in order.
4. Download the dataset using KaggleHub.
5. Train and evaluate the model.

## Disclaimer
This project is for educational and research purposes only. It is not intended for clinical diagnosis or medical decision-making.
