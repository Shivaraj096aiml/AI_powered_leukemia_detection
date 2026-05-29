# Leukemia Detection Using Deep Learning

## Project Overview

This project focuses on detecting leukemia from blood smear images using deep learning techniques. The system classifies images into two categories: **Healthy** and **Leukemia (Cancerous)**.

The project uses multiple pretrained convolutional neural network models to extract features and improve classification performance.

## Deep Learning Models Used

The following pretrained architectures were used:

* ResNet
* ConvNeXt-Tiny
* EfficientNet

These models help capture complex patterns in blood smear images for accurate disease detection.

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Dataset

The dataset consists of blood smear microscopic images categorized into:

* Healthy cells
* Leukemia cells

Images were preprocessed and resized before being used for model training.

## Project Workflow

1. Import and preprocess dataset
2. Perform data visualization and analysis
3. Apply data augmentation techniques
4. Train deep learning models
5. Evaluate model performance
6. Save trained model

## Model Evaluation

The model performance was evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report
* Training and Validation Loss Graphs

## Project Structure

```
leukemia-detection/
│
├── notebook/
│   └── leukemia_detection.ipynb
│
├─
│   
│
├── dataset/
│
├── requirements.txt
└── README.md
```

## How to Run the Project

1. Clone the repository
2. Install required libraries

```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```
jupyter notebook
```

4. Run all cells to train and evaluate the model.

## Future Improvements

* developing project for classifying sub types of leukemia like(ALL , AML, CLL, CML)
* Improve accuracy using larger datasets.
* Introducing Explainable-AI into our project.

## Author
S Shivaraj
AI/ML Project developed as part of my final year project.
