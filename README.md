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

## 🧠 Key Learnings

> This project demonstrated how complex systems can be effectively modeled and solved using a combination of mathematical reasoning, visual analysis and programming. It bridges the gap between abstract math and real-world problem-solving through simulation.

## ⚠️ Important Note
The specific values used in this simulation results in an inconsistent system of equations. However, the methodology and code are general and will work correctly for any set of traffic flow values that maintain consistency (i.e. where total inflow equals total outflow at each node).
> Feel free to modify the input values to test different traffic scenarios.

## 💻 Files in This Repository

| File | Description |
|------|-------------|
| `traffic_control.ipynb` | Python script with matrix formulation and solution using NumPy |
| `docs_to_learn` | Desmos-style traffic network visualization & Text-based system of equations used for modeling |
