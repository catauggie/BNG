# Biogas Plant Optimization — Multi-Objective Modeling

This repository contains the implementation of a multi-objective optimization (MOO) model for assessing biogas plant performance, focusing on trade-offs between total cost (TC), greenhouse gas emissions (GHG), and energy revenue (ER). The model and visualizations support a scientific article on sustainable biogas system design.

## 📁 Repository Contents

- **`MOO model.ipynb`** — Jupyter Notebook implementing the full MOO framework, including:
  - Definition of objective functions (cost, emissions, revenue, etc.)
  - Operational and environmental constraints
  - Optimization using evolutionary algorithms
  - Visualization of Pareto fronts in 2D and 3D

- **`PF_2D_subplots.pdf`** — Set of 2D Pareto front plots:
  - Total Cost vs. GHG Emissions  
  - Total Cost vs. Energy Revenue  
  - GHG Emissions vs. Energy Revenue  

- **`PF3D_real.pdf`** — 3D Pareto front plot:
  - Simultaneously shows trade-offs among TC, GHG, and ER
  - Highlights a “compromise zone” of robust, balanced solutions

## 📌 Applications

This repository is intended for:
- Researchers in sustainable energy and waste-to-energy systems
- Developers working on optimization of resource recovery technologies
- Supporting material for a scientific publication on MOO-based scenario analysis

## 📄 Publication

The model, plots, and results are part of the forthcoming article:  
**"Multi-Objective Optimization of Biogas Systems: Techno-Economic and Environmental Trade-Offs"**, 2025 (under preparation).

## ⚙️ Requirements

To run the notebook locally, you’ll need:
- Python 3.8+
- Required libraries: `numpy`, `scipy`, `matplotlib`, `pandas`, `deap` (or any other MOO framework)

## 📜 License

This project is licensed under the MIT License. You are free to use and adapt it with appropriate credit.
