# ML From Scratch: Core Algorithms Explained

This repository is a step-by-step, code-first guide to the most foundational machine learning algorithms implemented entirely from scratch using NumPy.

Whether you're preparing for interviews, taking CS229, or simply want to build rock-solid ML intuition, these notebooks will take you from equations to working code with clear explanations and visualizations.

---

## Contents

### [Linear Regression](./1.linear_regression/)
Learn how machines make predictions by fitting straight lines. This section covers the core building blocks of supervised learning, modeling, optimization, and regularization.

Notebooks:
- `foundations.ipynb`: Least squares and normal equations from scratch
- `gradient_descent.ipynb`: Batch, stochastic, and mini-batch gradient descent
- `regularization.ipynb`: Lasso (L1) and Ridge (L2) to prevent overfitting
- `locally_weighted_lr.ipynb`: Non-parametric local models using kernel-weighted regression

---

### [Logistic Regression](./2.logistic_regression/)
Build intuition for classification tasks by exploring logistic regression from multiple angles, including Newton's method, perceptrons, GLMs, and multiclass softmax.

Notebooks:
- `foundations.ipynb`: Binary classification with sigmoid + log-loss
- `newtons_method.ipynb`: Fast second-order optimization using Hessians
- `perceptron.ipynb`: Early rule-based classifier using misclassification updates
- `glm.ipynb`: Logistic regression as a generalized linear model (GLM)
- `softmax.ipynb`: Extend logistic regression to handle multiple classes using softmax + cross-entropy

---

### [Generative Models](./3.generative_models/)
Understand how to model the data generation process and use Bayes’ Rule for classification. These models are interpretable and perform well when assumptions are met.

Notebooks:
- `gda.ipynb`: Gaussian Discriminant Analysis (shared covariance, class priors)
- `naive_bayes.ipynb`: Gaussian Naive Bayes (independence assumption across features)

---

## How to Use

Each notebook:
- Is self-contained and beginner-friendly
- Starts from mathematical intuition
- Implements models using **only NumPy**
- Includes plots, animations, or decision boundary visualizations

No prior ML library knowledge required.

---

## Why This Exists

Too many ML resources either:
- Jump straight to libraries without explaining the math
- Stay too theoretical without showing how to implement

This repo bridges that gap: **you'll understand AND implement**.

---
