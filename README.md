# CS5710 – Machine Learning
## Home Work 1

**Student Name:** Pavan Kumar Reddy   
**Course:** CS5710 Machine Learning  
**Semester:** Spring 2026    

---

## Assignment Overview

This assignment implements Linear Regression using two different approaches:

1. Closed-form solution (Normal Equation)
2. Gradient Descent (implemented from scratch without using scikit-learn)

The objective is to compare both methods on the same synthetic dataset and analyze convergence behavior.

---

## Dataset Description

The dataset was generated using the linear model:

y = 3 + 4x + ε  

where:
- x ∈ [0, 5]
- ε is Gaussian noise
- Total samples: 200

A bias column of 1’s was added to the feature matrix before training.

---

## Closed-Form Solution (Normal Equation)

The model parameters were computed using:

θ = (XᵀX)⁻¹Xᵀy

The estimated intercept and slope are printed in the notebook, and the fitted regression line is plotted.

---

## Gradient Descent Implementation

- Initial parameters: θ = [0, 0]
- Learning rate (η): 0.05
- Iterations: 1000
- Loss function: Mean Squared Error (MSE)

The loss curve (MSE vs iterations) is plotted to show convergence.

---

## Plots Included

 1. Raw dataset scatter plot  
 2. Closed-form fitted regression line  
 3. Gradient Descent fitted regression line  
 4. Combined comparison plot  
 5. Loss vs iterations plot  

---

## Results & Comparison

The Gradient Descent solution converges to nearly the same intercept and slope as the closed-form solution.  
The loss decreases smoothly over iterations and stabilizes, confirming correct optimization.  
Both approaches produce nearly identical regression lines.

---


