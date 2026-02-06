# 🧬 Portfolio Optimization with Genetic Algorithm

This repository contains a two-stage optimization approach for portfolio optimization using Python.

The first stage applies the **Markowitz Mean-Variance Model** to generate an initial portfolio solution,  
which is then refined in the second stage using a **Genetic Algorithm** to achieve better optimization results.

---

## Project Structure
-  **Stage 1 – Markowitz Model**
  - Mean-Variance portfolio optimization
  - Expected return and risk (variance) calculation

-  **Stage 2 – Genetic Algorithm**
  - Portfolio optimization using evolutionary computation
  - Improvement of portfolio weights from Markowitz results

---

## Tools & Libraries
- Python
- NumPy
- Pandas
- Matplotlib

---

## Features
- Expected return and portfolio risk calculation
- Markowitz efficient portfolio generation
- Genetic Algorithm components:
  - Selection
  - Crossover
  - Mutation
  - Fitness evaluation

---
## Results
The Genetic Algorithm successfully identifies portfolio weights that:
- Maximize expected return for a given level of risk, or
- Minimize risk under return constraints

This approach demonstrates the effectiveness of metaheuristic methods in solving financial optimization problems.
