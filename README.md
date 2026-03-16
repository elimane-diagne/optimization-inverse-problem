# Inverse Problem and Optimization Methods

This project studies the resolution of an **inverse problem using numerical optimization techniques**.

The goal is to estimate unknown parameters of a mathematical model by minimizing the difference between **observed data and simulated results**.

The project includes both:

* the **forward problem** (simulation without optimization)
* the **inverse problem** solved using optimization methods.

---

# Inverse Problem

An inverse problem aims to determine unknown parameters ( p ) of a model such that

simulated data matches observed data.

The problem can be written as

minimize

J(p) = || u(p) − u_obs ||²

where

* (u(p)) : model prediction
* (u_{obs}) : observed data
* (J(p)) : cost function

---

# Optimization Methods

Several numerical techniques are explored:

* Sensitivity method
* Adjoint method
* Projected gradient method
* Uzawa method

These methods are commonly used in **optimal control and PDE-constrained optimization**.

---

# Repository Structure

```
optimization-inverse-problem
│
├── notebooks
│   ├── forward_problem.ipynb
│   └── inverse_problem.ipynb
│
├── docs
│   └── Beamer_PI.pdf
│
└── README.md
```

---

# Notebooks

### Forward problem

`forward_problem.ipynb`

Simulation of the model without optimization.

---

### Inverse problem

`inverse_problem.ipynb`

Estimation of unknown parameters using optimization techniques.

---

# Applications

Inverse problems appear in many scientific fields:

* parameter identification
* medical imaging
* fluid mechanics
* geophysics
* machine learning

---

# Author

Elimane Diagne

---

# License

Educational project.
