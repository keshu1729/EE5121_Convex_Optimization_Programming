# EE5121 – Convex Optimization Programming Assignments

This repository contains implementations and reports for two programming assignments from the **EE5121: Convex Optimization** course at **IIT Madras**.  
The assignments explore **logistic regression**, **mirror descent**, and **accelerated mirror descent** through mathematical derivations, algorithm implementations, and performance comparisons.

---

## 📂 Contents

### **Assignment 1 – Logistic Regression with Gradient Descent**
- **Goal:** Implement logistic regression from scratch using gradient descent and validate on synthetic and real-world datasets.
- **Topics Covered:**
  - Derivation of logistic regression gradient.
  - Sigmoid function visualization.
  - Manual gradient descent updates.
  - Convergence analysis.
- **Datasets:**
  - Synthetic dataset (scikit-learn `make_classification`).
  - Real-world dataset (`load_breast_cancer` from scikit-learn).
- **Results:**
  - Test accuracy: **97–99%** on breast cancer dataset.
  - Smooth convergence observed.
- **Key Insight:** Gradient descent implemented from scratch can achieve high accuracy with proper feature scaling and bias handling.

---

### **Assignment 2 – Mirror Descent & Accelerated Mirror Descent**
- **Goal:** Implement and compare **Mirror Descent (MD)** and **Accelerated Mirror Descent (AMD)** for convex problems.
- **Problems Solved:**
  1. Logistic Regression with Entropy Mirror Map.
  2. Quadratic Objective Function.
  3. Log-Sum-Exp Objective Function.
- **Topics Covered:**
  - Entropy mirror map derivation.
  - Convergence analysis of MD vs. GD.
  - Performance boost with AMD.
- **Results:**
  - AMD consistently converges faster than MD for smooth convex problems.
  - Stable convergence observed for MD; AMD provides significant speed-up.
- **Key Insight:** Acceleration techniques like AMD are especially effective for smooth convex optimization problems.

---

## 🛠️ Technologies Used
- **Languages:** Python  
- **Libraries:** NumPy, Matplotlib, scikit-learn  
- **Concepts:** Gradient Descent, Logistic Regression, Mirror Descent, Accelerated Mirror Descent, Convex Optimization.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/convex-optimization.git
   cd convex-optimization
