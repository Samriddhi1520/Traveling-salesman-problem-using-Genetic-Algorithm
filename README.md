# 🚀 Genetic Algorithm for Travelling Salesman Problem (TSP)

This demonstrates how a **Genetic Algorithm (GA)** can be applied to solve the **Travelling Salesman Problem (TSP)** — finding the shortest possible route that visits all cities exactly once and returns to the starting point.

---

## 🧠 Algorithm Workflow
1. **Initialization** – Generate a random population of routes.  
2. **Fitness Evaluation** – Calculate route distances using Euclidean distance.  
3. **Selection** – Pick the best-performing routes (shortest distances).  
4. **Crossover (OX)** – Combine two parent routes to create a child route.  
5. **Mutation** – Swap cities in a route with a small probability to maintain diversity.  
6. **Update** – Track the best route and shortest distance.  
7. **Repeat** – Iterate for multiple generations until convergence.  

---

## ✨ Features
- ✅ Random population initialization  
- ✅ Fitness evaluation (distance calculation)  
- ✅ Selection of top-performing routes  
- ✅ Order crossover (OX) for new route generation  
- ✅ Mutation for diversity  
- ✅ Visualizations:  
  - 📍 Best route plotted on a 2D map  
  - 📉 Distance improvement over generations  
  - 📊 Population distance distribution histogram  
  - 🌌 State space visualization using **MDS** (Multi-Dimensional Scaling)  

---

## 📊 Example Outputs

### 🔹 Best Route Visualization  
Displays the optimal route discovered by the GA.  
![Best Route]([best_route.png](https://github.com/Samriddhi1520/Traveling-salesman-problem-using-Genetic-Algorithm/blob/main/images/best_route.png))  

### 🔹 Distance Improvement Over Generations  
Shows how the shortest distance improves as generations evolve.  
![Distance Progress](distance_progress.png)  

### 🔹 Population Distance Distribution  
Illustrates diversity in route fitness within the population.  
![Population Histogram](population_hist.png)  

### 🔹 State Space Visualization (MDS)  
Visualizes routes in reduced 2D space using Multi-Dimensional Scaling (MDS).  

- **Generation 1**  
  ![State Space Gen 1](state_space1.png)  

- **Generation 5**  
  ![State Space Gen 5](state_space5.png)  

- **Generation 10**  
  ![State Space Gen 10](state_space10.png)  

---

## 🛠️ Tech Stack
- **Python** 🐍  
- **NumPy** – numerical operations  
- **Matplotlib** – plotting & visualization  
- **scikit-learn (MDS)** – dimensionality reduction for state space plots  

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/genetic-algorithm-tsp.git

# Navigate to project folder
cd genetic-algorithm-tsp

# Run the program
python tsp_ga.py
