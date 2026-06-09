# DeepLearningAI Machine Learning Course Labs

A collection of practical Jupyter Notebook labs from the DeepLearningAI Machine Learning course, covering foundational concepts in linear regression, Python, NumPy, and vectorization.

## 📋 Contents

### Week 1: Linear Regression Foundations

#### **C1_W1_Lab03_Cost_function_Soln.ipynb**
Introduction to the cost function for linear regression with one variable.
- **Topics:**
  - Cost function computation: $J(w,b) = \frac{1}{2m} \sum_{i=0}^{m-1} (f_{w,b}(x^{(i)}) - y^{(i)})^2$
  - Cost function intuition and visualization
  - 3D and contour plot visualization
  - Understanding the convex loss surface (soup bowl visualization)
- **Practical Skills:** Implementing cost calculations, visualizing optimization landscapes

#### **C1_W1_Lab04_Gradient_Descent_Soln.ipynb**
Practical implementation of gradient descent algorithm for linear regression.
- **Topics:**
  - Gradient computation with partial derivatives
  - Gradient descent update rules: $w = w - \alpha \frac{\partial J}{\partial w}$
  - Learning rate effects (convergence vs. divergence)
  - Cost reduction monitoring and convergence analysis
  - Prediction on new data
- **Practical Skills:** Implementing gradient descent, tuning learning rates, analyzing convergence

### Week 2: NumPy & Multiple Variable Regression

#### **C1_W2_Lab01_Python_Numpy_Vectorization_Soln.ipynb**
Introduction to Python NumPy for scientific computing.
- **Topics:**
  - NumPy arrays and basic operations
  - Vector indexing and slicing
  - Vector-vector element-wise operations
  - Vector dot products
  - Matrix creation and manipulation (shape, indexing, slicing)
  - Vectorization vs. for-loop performance comparison
- **Practical Skills:** NumPy fundamentals, vector operations, performance optimization

#### **C1_W2_Lab02_Multiple_Variable_Soln.ipynb**
Extension of linear regression to multiple features.
- **Topics:**
  - Matrix notation for multi-feature datasets: $X$ (m×n), $y$ (m,), $w$ (n,)
  - Model prediction: $f_{w,b}(x) = w \cdot x + b$
  - Cost function with multiple variables
  - Gradient computation for multiple parameters
  - Gradient descent implementation and convergence
- **Practical Skills:** Multi-variable linear regression, vectorized implementations, feature scaling awareness

## 🎯 Learning Objectives

By working through these labs, you will:
- ✅ Master linear regression from first principles
- ✅ Understand cost functions and optimization
- ✅ Implement gradient descent algorithm
- ✅ Leverage NumPy for efficient numerical computation
- ✅ Scale from single-variable to multi-variable regression
- ✅ Visualize and debug machine learning algorithms

## 🔧 Requirements

- Python 3.7+
- NumPy
- Matplotlib
- Jupyter Notebook/Lab

## 🚀 Getting Started

1. Clone or download this repository
2. Install dependencies:
   ```bash
   pip install numpy matplotlib jupyter
   ```
3. Open any notebook in Jupyter:
   ```bash
   jupyter notebook
   ```
4. Run cells sequentially to understand the concepts and implementations

## 📊 Course Structure

These labs follow the DeepLearningAI Machine Learning Specialization (Course 1) progression:
- **Week 1**: Introduction to linear regression with single variables
- **Week 2**: Python/NumPy fundamentals and extension to multiple variables

## 💡 Key Concepts

- **Linear Regression Model**: $f_{w,b}(x) = wx + b$
- **Cost Function**: Measures prediction error (mean squared error)
- **Gradient Descent**: Iterative optimization algorithm to minimize cost
- **Vectorization**: Using NumPy for efficient matrix operations
- **Learning Rate**: Controls step size in gradient descent

## 📝 Notes

- All notebooks are solution files (implementations are complete)
- Extensive comments and markdown explanations throughout
- Includes visualization code for understanding algorithm behavior
- Focus on implementation details and mathematical intuition

## 🎓 Course Source

Materials adapted from the DeepLearningAI Machine Learning Specialization.

---

**Author**: Stephen Tang  
**Repository**: DeepLearningAI-Machine-Learning
