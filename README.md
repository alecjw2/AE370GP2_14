# AE370 Group Project 2 (Team 14) - 2D Wave Simulation for Aircraft Defect Inspection 

This repository contains a numerical simulation of wave propagation on a 2D membrane. We use the wave equation to create a way of detecting material defects on aircraft in an efficient and not intrusive manner.

The project includes Python scripts for computing the wave dynamics and visualizing the results, as well as a collection of output images demonstrating the system's behavior over time.

---

## 📁 Contents

- `WavePlots.ipynb` — Main simulation script that implements the finite difference method to solve the 2D wave equation. This file also contains all the code that generates and plots the error convergence plots. 

- `Stability.ipynb` — This python script contains the 2 code blocks that plot the stability regions for both the RK4 and Crank-Nicolson methods. 

- `images/` — Directory containing output figures (e.g., wave snapshots at various time steps).

- `DefectPlots.ipynb` — File containing the code that computes the solution with material defects

- `README.md` — This file.

- `AE370GP2_14.pdf` — File containing the formal report. 

---

## 🧠 Project Overview

This project numerical solves the 2D wave equation:

$$
\frac{\partial^2 u}{\partial t^2} = c^2 \left( \frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} \right)
$$

using the method of lines. Our version of the method of lines uses a centered finite difference method and the Crank-Nicolson time stepping method. 
The goal is to simulate the displacement \( u(x, y, t) \) of a membrane under initial excitation and observe wave propagation patterns.

---

## ⚙️ Requirements

Make sure you have the following installed:

- Python 3.8+
- NumPy
- Matplotlib

