# Linear Algebra for AI & Machine Learning

## Why Linear Algebra Matters in AI
Linear algebra is the backbone of machine learning and deep learning.
Data, model parameters, and transformations are all represented using vectors and matrices.

In simple terms:
- A **data point** = vector
- A **dataset** = matrix
- A **model** = matrix operations + optimization

---

## Scalars, Vectors, and Matrices

### Scalars
- Single numbers
- Example: learning rate, bias

### Vectors
- Ordered list of numbers
- Used to represent:
  - Features of one data point
  - Model weights

Example:
x = [x₁, x₂, x₃]

### Matrices
- Collection of vectors
- Used to represent datasets and transformations

Example:
- Dataset with `m` samples and `n` features → m × n matrix

---

## Vector Operations

### Vector Addition
- Combines two vectors element-wise
- Used when aggregating information

### Dot Product
- Measures similarity between vectors
- Fundamental to:
  - Linear regression
  - Neural networks

---

## Matrix Multiplication

- Core operation in ML models
- Enables transformation of data
- Order matters (A × B ≠ B × A)

In neural networks:
- Inputs × weights = output

---

## Identity and Inverse Matrices

- Identity matrix behaves like number 1
- Inverse matrix helps "undo" transformations
- Important in optimization and linear regression

---

## Eigenvectors and Eigenvalues (High-Level)
- Describe directions where transformations scale data
- Used in:
  - PCA (dimensionality reduction)
  - Feature extraction

No deep math here — focus on intuition.

---

## Key Takeaways
- ML is mostly matrix math
- Efficient linear algebra = efficient ML models
- Understanding this reduces ML from “magic” to math

---
