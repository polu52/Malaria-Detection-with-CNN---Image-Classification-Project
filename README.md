
# 🦠 Malaria Detection with CNN - Image Classification Project

This deep learning project aims to classify cell images as infected or uninfected with malaria using Convolutional Neural Networks (CNN). It contributes to faster and more accurate medical diagnostics in malaria-endemic regions.

> 💾 **Dataset Source:** [NIH Malaria Dataset](https://lhncbc.nlm.nih.gov/publication/pub9932)

## 📊 Project Overview

The model is trained on a publicly available dataset of thin blood smear images labeled as either parasitized (infected) or uninfected. It applies convolutional layers, pooling, and fully connected layers to build an end-to-end image classification system.

## 📁 Files

- `Image Classification with CNN for Malaria Data.ipynb`: Jupyter Notebook with complete code including preprocessing, model building, training, evaluation, and predictions.

## 🧠 Technologies Used

- Python 🐍
- TensorFlow / Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

## 🔍 Key Steps

1. **Dataset Loading**
   - Images of blood cells categorized into 'Parasitized' and 'Uninfected' folders.

2. **Image Preprocessing**
   - Resizing images (e.g., 128x128 or 64x64)
   - Normalization and reshaping

3. **Model Architecture**
   - Convolutional Layers
   - MaxPooling Layers
   - Flatten + Dense Layers
   - Sigmoid activation in output for binary classification

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
   - Training vs Validation loss/accuracy plots

## 📈 Results

- High accuracy in detecting malaria-infected cells
- Effective generalization on unseen data
- Visualization of true/false predictions

## 💡 Real-World Application

- AI-assisted malaria diagnostics
- Remote or low-resource medical screenings
- Medical image analysis in developing regions

