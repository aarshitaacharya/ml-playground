# Linear Regression

Linear regression is the foundation of machine learning. Before diving into complex algorithms, mastering linear regression gives you essential intuition about how ML models work, optimization, and regularization techniques.

## What You'll Learn

This repository contains progressive notebooks that build your understanding from the ground up:

### 1. `foundations.ipynb`
**Building Linear Regression from Scratch**
- Implement linear regression without using libraries
- Understand the mathematical foundation (least squares)
- Work with simple synthetic data
- Learn about cost functions and model evaluation
- Build intuition for what's happening "under the hood"

### 2. `gradient_descent.ipynb` 
**Three Flavors of Gradient Descent**
- **Batch Gradient Descent**: Uses entire dataset for each update
- **Stochastic Gradient Descent**: Updates with one sample at a time
- **Mini-batch Gradient Descent**: Balances efficiency and stability
- Compare convergence behavior and computational trade-offs
- Visualize how different approaches affect learning

### 3. `regularization.ipynb`
**Lasso vs Ridge Regularization**
- Prevent overfitting with L1 and L2 regularization
- **Ridge**: Shrinks coefficients, handles multicollinearity
- **Lasso**: Performs feature selection, creates sparse models
- Understand the bias-variance trade-off
- Learn when to use each technique

### 4. `locally_weighted_lr.ipynb`
**Locally Weighted Linear Regression (LWLR)**
- Non-parametric extension of linear regression
- Fits a separate linear model for each query point using weighted least squares
- Nearby points are given higher weight (Gaussian kernel)
- Understand the effect of the bandwidth parameter \( \tau \) on bias and variance
- Visualize model flexibility by adjusting local weighting

## Learning Resources

The concepts in these notebooks are based on the following educational resources:

- [Stanford CS229 Lecture Notes](https://cs229.stanford.edu/main_notes.pdf)
- [Stanford CS229 - Andrew Ng](https://www.youtube.com/watch?v=4b4MUYve_U8&t=4421s)
- [Normal Equation Derivation](https://www.youtube.com/watch?v=g8qF61P741w) 
- [Assumptions of LR](https://www.youtube.com/watch?v=sDrAoR17pNM&t=319s)
- [Ridge Regularization - StatQuest](https://www.youtube.com/watch?v=Q81RR3yKn30)
- [Lasso Regularization - StatQuest](https://www.youtube.com/watch?v=NGf0voTMlcs)
- [Locally Weighted & Logistic Regression - Andrew Ng](https://www.youtube.com/watch?v=het9HFqo1TQ)
