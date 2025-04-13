# Kuramoto Model on Complex Networks

This project includes simulation and analysis of the **Kuramoto model** on three types of complex networks:

- Erdős–Rényi Random Graph (ER)
- Barabási–Albert Scale-Free Network (SF)
- Watts–Strogatz Small World Network (SW)

---

## Description

I used C++ (with Runge-Kutta integration) to simulate the phase synchronization dynamics of N = 1000 oscillators on different network topologies.

The **Kuramoto equation** is integrated using custom-written numerical solvers, and order parameters `r(t)` are extracted.

Python was used to:
- Load the generated networks
- Plot the graph structures
- Compute and visualize degree distributions
