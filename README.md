# 🎬 Film Genre Classification with CNN and LSTM

This repository contains the implementation of a deep learning assignment for a module focused on **GPU-accelerated data processing using TensorFlow and Keras**. The task involves building and evaluating **Convolutional Neural Network (CNN)** and **Long Short-Term Memory (LSTM)** models for classifying film genres from multimodal data (images and text).

## 📚 Learning Objectives
This project demonstrates the following skills and knowledge:
- 🚀 Understanding how GPUs can accelerate data processing.
- 🚀 Developing TensorFlow-based data processing pipelines.
- 🚀 Writing efficient data pipelines with `tf.data` API.
- 🚀 Building and training CNNs and LSTMs using TensorFlow and Keras.
- 🚀 Critically evaluating model performance.

## 📁 Dataset Overview
The dataset provided includes:
- **Film Posters**: JPEG images from IMDb.
- **Film Overviews**: Text descriptions from IMDb.

## 🔍 Project Tasks
### 1️⃣ Data Processing
- Implement an image processing function for film posters.
- Build an efficient data pipeline using TensorFlow's `tf.data` API.
- Process text data and build the vocabulary with `encoder.adapt()`.

### 2️⃣ Model Definition
- Construct and compile a **CNN model** for poster classification based on a predefined model summary.
- Build and compile a **Sequential LSTM model** with an embedding layer for overview text classification.

### 3️⃣ Model Training
- Define callbacks to log training progress.
- Train both models for a specified number of epochs.
- Evaluate and critically comment on the performance in a concise report.

## 🛠️ Tools & Frameworks
- **TensorFlow**
- **Keras**
- **Google Colab**

## 📈 Report
A 2–3-page report is included to critically analyze the models’ performance, highlighting results, challenges, and potential improvements.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/film-genre-classification.git
   cd film-genre-classification
