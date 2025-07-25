# Generative Models

Generative models learn the **joint probability distribution** $ P(x, y) $, and then use Bayes' Rule to infer the conditional distribution $ P(y \mid x) $. Unlike discriminative models (like logistic regression), generative models aim to understand **how the data was generated**.

This folder focuses on two foundational generative models for classification:

- **Gaussian Discriminant Analysis (GDA)**
- **Naive Bayes**

These models are efficient, interpretable, and surprisingly powerful, especially when their assumptions are valid.

---

## What You'll Learn

This directory includes progressive, from-scratch implementations of classic generative classifiers.

---

### 1. `gda.ipynb`  
**Gaussian Discriminant Analysis (GDA)**  
- Model each class as a **multivariate Gaussian** with a shared covariance matrix
- Estimate parameters: class priors (ϕ), means (μ₀, μ₁), and covariance (Σ)
- Derive decision boundaries using Bayes' Rule
- Implement GDA from scratch with NumPy
- Visualize decision boundaries and compare to logistic regression
- Understand how GDA benefits from assuming Gaussian-distributed features

---

### 2. `naive_bayes.ipynb`  
**Gaussian Naive Bayes from Scratch**  
- Assume **feature-wise independence** given the class label
- Model each feature $ x_i \mid y $ as a 1D **Gaussian**
- Estimate means and variances separately for each feature and class
- Implement Naive Bayes using NumPy
- Visualize decision boundaries on synthetic 2D data
---

## Learning Resources

These notebooks build upon classic ML references:

- [CS229 Lecture Notes – Andrew Ng](https://cs229.stanford.edu/main_notes.pdf)
- [Discriminative vs Generative – Andrew Ng (video)](https://www.youtube.com/watch?v=nt63k3bfXS0)

---