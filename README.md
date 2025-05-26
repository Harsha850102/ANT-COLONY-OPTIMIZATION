# 🐜 Ant Colony Optimization (ACO)

Ant Colony Optimization (ACO) is a **bio-inspired metaheuristic algorithm** modeled after how real ants find the shortest paths between their nest and food sources using pheromone trails. This project demonstrates how ACO can be applied to solve the **Traveling Salesman Problem (TSP)**.

---

## 🧠 What is Ant Colony Optimization (ACO)?

ACO is a probabilistic algorithm that uses the idea of **pheromone-based communication** to iteratively explore and optimize solutions. Inspired by the behavior of ants in nature, it works as follows:

- 🧪 **Pheromone Trails**: Virtual ants deposit pheromones on the paths they travel. Stronger pheromone trails indicate better solutions.
- 🔁 **Positive Feedback**: Good paths get reinforced over time, leading to faster convergence.
- 🔄 **Exploration + Exploitation**: ACO balances trying new paths and reinforcing known good ones.
- 🔗 **Graph-Based Problems**: Especially effective for routing, scheduling, and network design problems.

### 🧑‍🏫 Why is ACO Important?

- It works well for **NP-hard problems** where traditional algorithms struggle.
- It provides **near-optimal solutions** without exhaustive search.
- It is **highly adaptable** to dynamic, real-world environments.

## 📌 Project Overview
- **Group Members:**
  - Sreeja Kukkala
  - Harsha Vardhan Alladi
  - Madhan Mohan Madala

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
