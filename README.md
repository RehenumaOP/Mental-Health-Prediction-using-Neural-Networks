# 🧠 Mental Health Prediction using Neural Networks

## 📖 Project Description

This project focuses on predicting the prevalence of depressive disorders using machine learning techniques.
The dataset contains mental health statistics, and multiple neural network approaches are applied to analyze and predict outcomes.

The project is implemented using:

* NumPy (Neural Network from scratch)
* PyTorch
* TensorFlow

## 🎯 Objectives

* Analyze mental illness dataset
* Build neural network from scratch using NumPy
* Compare performance with PyTorch and TensorFlow
* Understand deep vs wide neural networks

## 📂 Dataset

* Dataset: Mental Illness Prevalence Dataset
* File used: `mental-illnesses-prevalence.csv`

## ⚙️ Project Workflow

1. Load dataset from Google Drive
2. Data preprocessing:

   * Remove unnecessary columns (Entity, Code)
   * Handle missing values
3. Feature & target selection
4. Data normalization
5. Train-test split (80% / 20%)

## 🤖 Models Implemented

### 1. NumPy Neural Network (From Scratch)

* One hidden layer
* ReLU activation function
* MSE loss function
* Manual forward & backpropagation

### 2. PyTorch Model

* Fully connected neural network
* Adam optimizer
* MSE loss

### 3. TensorFlow Model

* Sequential model
* Dense layers with ReLU activation
* Optimized using Adam

## 📊 Experiments

* Increase/decrease hidden neurons
* Deep vs Wide network comparison
* Performance comparison between:

  * NumPy
  * PyTorch
  * TensorFlow

## 📈 Results

* TensorFlow achieved the lowest loss
* PyTorch showed strong performance
* NumPy implementation helped understand core concepts

## 🚀 How to Run

1. Clone the repository:


git clone https://github.com/your-username/your-repo-name.git


2. Install required libraries:


pip install numpy pandas matplotlib torch tensorflow

3. Run the notebook:
jupyter notebook


## 📌 Future Improvements

* Add more advanced models (CNN / LSTM)
* Use larger dataset
* Build web interface (React + Node.js)
* Deploy as real-time prediction system
