# Logistic Regression

Logistic regression is a fundamental classification algorithm in machine learning. It builds upon linear regression but is used for predicting binary outcomes. Understanding logistic regression is crucial as it forms the basis for more complex models, especially in classification tasks.

## What You'll Learn

This repository contains progressive notebooks that gradually deepen your understanding of logistic regression:

### 1. `foundations.ipynb`
**Building Logistic Regression from Scratch**
- Implement logistic regression without using libraries
- Understand the mathematical foundation (sigmoid activation and log-loss)
- Work with simple synthetic data
- Learn how to optimize using gradient descent
- Build intuition for how the decision boundary is learned

### 2. `newtons_method.ipynb`
**Logistic Regression using Newton's Method**
- Implement logistic regression using a second-order optimization approach
- Compute both the **gradient** and the **Hessian** of the log-likelihood
- Apply Newton’s update rule to converge faster than gradient descent
- Understand the curvature of the loss surface using the Hessian
- Compare convergence behavior and efficiency with gradient descent

### 3. `perceptron.ipynb`
**Perceptron Algorithm for Binary Classification**
- Implement the Perceptron from scratch using NumPy
- Understand how it differs from logistic and linear regression
- Learn the misclassification-based update rule
- Visualize the decision boundary evolution over training
- Experiment with synthetic linearly separable data

### 4. `glm.ipynb`
**Logistic Regression as a Generalized Linear Model (GLM)**
- Understand how logistic regression fits into the broader GLM framework
- Use the **Bernoulli distribution** with a **logit link function**
- Implement gradient descent to optimize the log-likelihood
- Visualize convergence of the log-loss
- Plot the decision boundary learned by the model
- Build a foundation to extend GLM to Poisson, Gaussian, and others

## Learning Resources

The concepts in these notebooks are based on the following educational resources:

- [Stanford CS229 Lecture Notes](https://cs229.stanford.edu/main_notes.pdf)
- [Locally Weighted & Logistic Regression - Andrew Ng](https://www.youtube.com/watch?v=het9HFqo1TQ)
- [Perceptron & GLM - Anand Avati](https://www.youtube.com/watch?v=iZTeva0WSTQ) 