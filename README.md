# Life Improvement Optimization Framework

A structured data science and operations research pipeline utilizing mathematical programming to solve multi-variable optimization challenges for personal and professional efficiency.

## Overview
This project provides a rigorous framework for decision-making under constraints. By applying Linear and Quadratic Programming, we demonstrate how to optimize limited resources—whether minimizing daily dietary costs, allocating project budgets, or constructing high-performing financial portfolios—to achieve defined goals.

## Project Structure
- `Life_Improvement.ipynb`: Jupyter notebook containing the full mathematical modeling and implementation.
- `Life_Improvement_Report.pdf`: The final technical summary of the optimization models and findings.
- `Life Improvement.pdf`: The original assignment documentation.

## Key Phases
1. **Dietary Optimization (Linear Programming):** Minimized total daily expenditure while satisfying strict nutritional requirements (protein, carbohydrates, fats, vitamins) for 10 distinct food items.
2. **Project Management (Linear Programming):** Optimized resource allocation across 5 project activities, constrained by time limits, total resource capacity, and minimum profit targets.
3. **Portfolio Selection (Quadratic Programming):** Implemented the Markowitz Portfolio Optimization approach to maximize expected returns while minimizing risk (variance) for 10 financial assets, balanced by a risk-aversion parameter ($\lambda = 0.5$).

## Key Technologies
- **Python:** Primary language for model implementation.
- **cvxpy:** Domain-specific language for convex optimization.
- **NumPy:** Efficient matrix and vector computation.
- **LaTeX:** Typesetting for technical documentation.

## Key Findings
| Problem Type | Optimization Method | Outcome |
| :--- | :--- | :--- |
| **Dietary** | Linear Programming | Optimal cost of 186.16 |
| **Project Management** | Linear Programming | Optimal cost of 50.00 |
| **Portfolio Selection** | Quadratic Programming | R² equivalent Return 19.68%, Risk 2.89 |

## Author
**Sepehr Barekati**
