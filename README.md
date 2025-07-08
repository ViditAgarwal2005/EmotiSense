# Facial Emotion Recognition using CNN on FER-2013

This repository contains a Convolutional Neural Network (CNN) model trained on the [FER-2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013) for real-time facial emotion recognition. The model classifies facial expressions into one of seven emotion categories: *Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral*.

---

## 🚀 Key Features

- Trained on the FER-2013 dataset with over 35,000 grayscale facial images
- Achieves *89% validation accuracy* and *F1 Score of 0.97*
- Built using *TensorFlow/Keras*
- Supports real-time predictions
- Includes visualization of training metrics (loss and accuracy)

---

## 📁 Dataset

The model is trained on the *FER-2013* dataset, a benchmark dataset for facial expression recognition, containing:

- 35,887 grayscale images (48x48 pixels)
- 7 emotion classes

You can download the dataset from [here](https://www.kaggle.com/datasets/msambare/fer2013).

---

## 🧠 Model Architecture

The CNN architecture consists of:

- Multiple convolutional and pooling layers
- Batch Normalization for stability
- Dropout layers to prevent overfitting
- Fully connected dense layers
- Final softmax layer for emotion classification

---

## 📊 Performance

| Metric         | Value     |
|----------------|-----------|
| Validation Accuracy | 89%       |
| F1 Score       | 0.97      |
| Number of Classes | 7       |
