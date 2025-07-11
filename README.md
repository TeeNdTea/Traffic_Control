# 🚦 Traffic Flow Modeling using Graph, Linear Algebra & Python
This project simulates a **4-intersection one-way traffic network** and models it mathematically to determine unknown traffic flow rates. By applying **graph theory**, a **system of linear equations** and solving it using **Python (NumPy)**. The project demonstrates how complex real-world systems can be simplified and solved analytically.

## 📌 Problem Statement

- A city-like road network with 4 **one-way streets** and **4 intersections** (nodes A, B, C, D).
- Cars enter and exit from different directions with known and unknown flow rates.
- The objective is to determine the unknown traffic flows **X₁, X₂, X₃, X₄** such that:
  - At every intersection: **Traffic In = Traffic Out**
  - The entire network is balanced

## 📊 Concepts Applied

- **Graph Theory**: Nodes = intersections, Edges = one-way roads  
- **System of Linear Equations**: Based on flow conservation at each node  
- **Matrix Representation**: For solving the system with Python  
- **Python (NumPy)**: Used `numpy.linalg.solve()` to find the unknowns  
- **Desmos**: Visualized the traffic flow and node relationships graphically
