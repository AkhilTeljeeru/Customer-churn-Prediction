# Customer-churn-Prediction
Project Overview

This project marks the completion of my learning journey in PyTorch fundamentals, covering topics from tensors and automatic differentiation to building, training, evaluating, and saving/loading neural network models.

As my first end-to-end Multi-Layer Perceptron (MLP) project, I developed a Customer Churn Prediction system using the Telco Customer Churn dataset. The model predicts whether a telecom customer is likely to cancel their subscription based on customer demographics, services, and account information.

What I Learned

During this project, I applied concepts including:

PyTorch Tensors
Automatic Differentiation (Autograd)
Neural Networks with nn.Module
Custom Datasets and DataLoaders
Training and Validation Loops
Loss Functions
Optimizers (Adam)
Binary Classification
Model Evaluation
Saving and Loading Models
End-to-End Deep Learning Workflow
Problem Statement

Telecom companies face significant losses when customers switch to competitors. Since retaining customers is more cost-effective than acquiring new ones, predicting customer churn can help businesses take proactive retention measures.

Dataset
Telco Customer Churn Dataset (Kaggle)
Binary Classification Problem
Target Variable: Churn (Yes/No)
Model Architecture
Input Layer
     ↓
Linear Layer
     ↓
ReLU
     ↓
Linear Layer
     ↓
ReLU
     ↓
Output Layer (1 Neuron)
Technologies Used
Python
PyTorch
Pandas
NumPy
Scikit-learn
Results
Model Type: Multi-Layer Perceptron (MLP)
Loss Function: BCEWithLogitsLoss
Optimizer: Adam
Accuracy Achieved: 73.93%
Key Takeaway

This project helped me understand the complete deep learning pipeline, from data preprocessing and model development to evaluation and model persistence. It serves as my first practical implementation of an MLP after completing my PyTorch learning journey.

Future Improvements
Hyperparameter tuning
Feature engineering
Handling class imbalance
Cross-validation
Comparing MLP with other machine learning models

Status: Completed ✅
Learning Milestone: First End-to-End MLP Project in PyTorch 🚀
