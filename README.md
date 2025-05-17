# Optimization Methods – ME609 Course Project

This repository contains the course project for **ME609 (Optimization Methods)** completed during the first year of my Master's program. The goal of the project was to implement and experiment with various optimization techniques, starting from single-variable methods and progressing to multivariable and constrained optimization algorithms.

## 📁 Project Structure

The project is organized into three main parts, each implemented in a separate Python file:

### 1. Single-Variable Optimization

**File:** `single_variable_optimization.py`

This module includes two fundamental bracketing methods for optimizing single-variable functions:

- **Bounding Phase Method**: Determines an interval containing the local minimum.
- **Interval Halving Method**: Narrows the interval to locate the minimum with higher precision.

### 2. Multivariable Optimization

**File:** `multivariable_optimization.py`

This module focuses on unconstrained multivariable optimization using:

- **Conjugate Gradient Method**: A powerful method for large-scale optimization problems that improves upon gradient descent by considering conjugate directions for faster convergence.

### 3. Constrained Optimization

**File:** `constrained_optimization.py`

This module handles multivariable optimization under constraints using two different techniques:

- **Bracket Operator Penalty Method**: Penalizes constraint violations to guide the optimizer into feasible regions.
- **Method of Moments**: An approach for handling constraints by converting them into a system that approximates feasibility conditions.

## 🚀 How to Run

Each file is self-contained and can be executed directly. Simply clone the repository and run the desired script using Python:

```bash
python single_variable_optimization.py
python multivariable_optimization.py
python constrained_optimization.py
