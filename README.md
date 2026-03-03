# 🧠 Neural Network Regression Model (TensorFlow)
# 📌 Overview

This project implements a fully connected neural network using TensorFlow/Keras to perform regression on structured tabular data with 8 numerical input features.

The model predicts a continuous target variable using Mean Squared Error (MSE) as the loss function and evaluates performance using MAE and R² score.

This project demonstrates:

Proper regression modeling with neural networks

Data preprocessing and feature scaling

Train-test splitting

Model evaluation using multiple regression metrics

# 📊 Problem Type

Task: Supervised Regression

Input: 8 numerical features

Output: 1 continuous value

Dataset Example: Median House Value (MedHouseVal)

Because the target variable is continuous, the model uses:

Linear output layer

Mean Squared Error loss

# 🏗 Model Architecture

Input Layer (8 features)
        ↓
Dense Layer (64 neurons, ReLU)
        ↓
Dense Layer (64 neurons, ReLU)
        ↓
Dense Layer (1 neuron, Linear Output)
🔎 Design Rationale

ReLU activation allows nonlinear learning.

Two hidden layers increase representational power.

Single output neuron is standard for regression.

No activation on output → allows unrestricted numeric prediction.

# 📌 Key Learning Outcomes

This project demonstrates understanding of:

Regression vs classification modeling

Neural network architecture design

Proper loss function selection

Feature scaling importance

Model evaluation using multiple metrics

Train-test separation best practices

# 💡 Possible Improvements

To extend this project further:

Add EarlyStopping callback

Compare with Linear Regression baseline

Perform hyperparameter tuning

Add residual analysis

Visualize prediction vs actual values

Implement cross-validation
