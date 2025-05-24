# Image Classification of Types of Rice Grains 

Welcome to this image classification project where I trained a Convolutional Neural Network (CNN) to identify different varieties of rice grains. Rice is a staple food for over half the world's population, and being able to automatically classify rice types can be incredibly useful in quality control, agriculture, and food tech. In this project, I worked with a dataset of 75,000 grain images across five rice varieties:

- Arborio
- Basmati
- Ipsala
- Jasmine
- Karacadag

## 📦 Dataset
- 📥 Download Link: [Rice Image Dataset on Kaggle](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)
- Source: Kaggle, provided by Murat Koklu
  
Using deep learning (specifically CNNs), the goal was to build a model that could accurately classify these rice varieties from raw image data.
## 🧰 Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- OpenCV (for image handling)
- Data Augmentation techniques
- Jupyter Notebook

## 🔍 What I Did
- Preprocessed the image dataset (resizing, normalization)
- Built and trained two CNN models (a simple one and a deeper one)
- Used data augmentation to reduce overfitting
- Evaluated the models using accuracy and loss curves
- Compared performance across both models

## 🚀 Results
The simple CNN achieved ~98% accuracy
The complex CNN hit ~99% accuracy on the training set

Validation performance remained strong, showing that the model generalizes well

Interestingly, the simple model held up just as well as the deeper one showing that sometimes less is more, especially with clean and well-structured data.

