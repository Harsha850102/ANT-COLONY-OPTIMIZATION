# 🐜 Ant Colony Optimization (ACO)

This project demonstrates the **Ant Colony Optimization (ACO)** algorithm applied to the **Traveling Salesman Problem (TSP)**. The algorithm simulates the behavior of real ant colonies in finding the shortest path using pheromone trails.

## 📌 Project Overview

- **Course:** QMST 5332.003
- **Group Members:**
  - Sreeja Kukkala (swt36)
  - Harsha Vardhan Alladi (nfb15)
  - Madhan Mohan Madala (cck60)

## 📂 Files Included

| File | Description |
|------|-------------|
| `ACO_CODE.ipynb` | Python code implementing ACO for TSP |
| `report/ACO_REPORT_Group7.pdf` | Full academic report with background, methodology, results, and references |
| `presentation/ACO_PPT_Group7.pptx` | Final presentation slides for demo and explanation |

## 🧠 Key Concepts

- Pheromone trails and heuristic distance
- Probabilistic path construction
- Iterative pheromone update and convergence
- Applied to TSP with cities [A, B, C, D, E]

## ⚙️ Parameters Used

- α (pheromone influence): 1  
- β (heuristic influence): 5  
- ρ (evaporation rate): 0.5  
- Q (pheromone constant): 100  

## 🚀 Result

- Best Path: `[E → D → C → A → B → E]`
- Shortest Distance: `9 units`
- Converged in `54 iterations`

## 📦 Setup

To run this project:

```bash
pip install -r requirements.txt
