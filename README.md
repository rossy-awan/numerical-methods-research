# Numerical Methods Research

This repository contains research on numerical methods and computational experiments developed using Python and Jupyter Notebook.

The work focuses on the development and evaluation of numerical methods for solving mathematical and physical problems, with particular attention to accuracy, convergence, stability, and computational cost.

## Repository Structure

The repository is organized by the type of mathematical or physical problem being investigated. The repository currently contains:

* **`pde/`** – Research on numerical methods for partial differential equations. The current study investigates matrix-exponential approximations for time propagation in the one-dimensional time-dependent Schrödinger equation using Taylor, Inverse-Taylor, and diagonal Padé approximations with scaling and squaring and high-order central-difference discretization. The framework can also be applied to other linear evolution equations, including the **Dirac, heat, and advection equations**.

Additional categories will be added as new research studies are completed.

## Python Libraries & Environment

The research is developed using:

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook / JupyterLab
* **Libraries:** `numpy`, `scipy`, `matplotlib`, `pandas`

### Installation

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```