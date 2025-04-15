# 🐜 Geospatial Trajectory Optimization using Ant Colony Optimization (ACO)

This project implements the **Ant Colony Optimization (ACO)** algorithm to solve the **Geospatial Traveling Salesman Problem (Geo-TSP)**. Given a set of GPS coordinates (latitude-longitude), the algorithm finds the shortest path that visits each location exactly once and returns to the starting point — optimized for real-world geography using the **Haversine formula**.

---

## 🚀 Features

- 🌍 Accurate distance calculation using **Haversine formula**
- 🐜 Path optimization using **Ant Colony Optimization**
- 📍 Works on geospatial (latitude-longitude) data
- 🔁 Supports customizable parameters for ants, iterations, pheromone behavior
- 💡 Useful for logistics, delivery routing, urban planning, and smart mobility

---

## 🛠️ Technologies Used

- **Language**: Python 🐍
- **Libraries**:
  - `numpy` – for matrix operations
  - `math` – for geospatial math functions
- **Concepts**:
  - Ant Colony Optimization (ACO)
  - Haversine distance calculation

---

## 📌 How It Works

1. Input a list of geospatial coordinates.
2. Construct a distance matrix using the Haversine formula.
3. Initialize ants and pheromone trails.
4. Iteratively simulate ant movements:
   - Choose next nodes based on pheromone level and distance.
   - Update pheromones based on path quality.
5. Return the shortest path and total distance.


