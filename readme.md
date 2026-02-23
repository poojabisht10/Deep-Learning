# UCS761 – Deep Learning Lab Assignments

This repository contains my solutions to selected **Deep Learning laboratory assignments** for the course **UCS761**.  
The main objective of these experiments is to strengthen conceptual understanding by implementing core machine learning models **from scratch using NumPy**, without using high-level deep learning libraries.

---

## 📁 Repository Structure
```
├── UCS761_Lab3_Logistic_Regression_Soft_Decision_Model.ipynb
├── UCS761_Lab4_Multi_Linear_Regression_via_Linear_Perceptron.ipynb
├── UCS761_Lab5_Linear_Regression_From_Scratch.ipynb
├── UCS761_Lab6_Learning_to_Bend_a_Model.ipynb
├── README.md
```

---

## 🧪 Experiment 1: Logistic Regression as a Soft Decision Model

📘 **Notebook:**  
`UCS761_Lab3_Logistic_Regression_Soft_Decision_Model.ipynb`

### Objective
To analyze logistic regression as a **probability-based classification model** and understand how it improves upon hard decision models like the perceptron.

### Topics Covered
- Sigmoid activation and probability outputs
- Binary Cross-Entropy loss
- Gradient Descent optimization
- Effect of varying decision thresholds
- Comparison between perceptron and logistic regression

---

## 🧪 Experiment 2: Multiple Linear Regression using Linear Perceptron

📘 **Notebook:**  
`UCS761_Lab3_Multi_Linear_Regression_via_Linear_Perceptron.ipynb`

### Objective
To implement **multiple linear regression** using a perceptron-based linear model trained with a regression loss function.

### Topics Covered
- Regression vs classification concepts
- Linear forward computation (no activation)
- Mean Squared Error (MSE) loss
- Manual gradient calculation
- Gradient Descent for parameter updates
- Continuous prediction behavior

---

## 🧪 Experiment 5: Linear Regression Neuron using Gradient Descent (From Scratch)

📘 **Notebook:**  
`UCS761_Lab5_Linear_Regression_From_Scratch.ipynb`

### Objective
To understand how a **single linear neuron learns numeric predictions** using **gradient descent**, without using any machine learning libraries.  
The experiment predicts the **age of abalone** using physical measurements.

### Topics Covered
- Loading and exploring the Abalone dataset (UCI)
- Feature selection and justification
- Target transformation (`Age = Rings + 1.5`)
- Train-test split (manual)
- Input normalization using training statistics
- Linear forward pass
- Mean Squared Error (MSE) and Mean Absolute Error (MAE)
- Manual gradient computation for weights and bias
- Gradient Descent training loop
- Error analysis and bias observation

---

## 🧪 Experiment 6: Learning to Bend a Model (Non-Linear Regression)

📘 **Notebook:**  
`UCS761_Lab6_Learning_to_Bend_a_Model.ipynb`

### Objective
To understand **why linear models fail on non-linear data** and how introducing a **hidden layer with activation functions** allows the model to learn curved relationships.

This experiment builds a small neural network **entirely from scratch**.

### Topics Covered
- Creating a synthetic non-linear dataset
- Limitations of linear models
- Designing a model with a hidden layer
- Role of activation functions (ReLU)
- Importance of activation slopes
- Forward pass through multiple layers
- Mean Squared Error (MSE) loss
- Manual backpropagation
- Gradient-based parameter updates
- Observing how the model bends to fit data

---

## 🧠 Key Learning Outcomes

> - A single linear model can be used for both **classification and regression** by changing the loss function.  
> - Linear models can only represent straight-line relationships.  
> - Non-linearity comes from hidden layers and activation functions.  
> - Gradients provide direction for learning.  
> - Backpropagation is structured error flow, not magic.

---

## 🛠 Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Google Colab  

---

## 👤 Author
**Pooja Bisht**  
UCS761 – Deep Learning
