# Vehicle Routing Problem with Genetic Algorithm 🚚

This project solves a simplified Vehicle Routing Problem (VRP) using a Genetic Algorithm (GA) implemented with the **DEAP** library. The solution identifies optimal routes for a set of vehicles to visit multiple locations starting and ending at a depot while minimizing the total distance traveled and balancing the load among vehicles.

---

## 📂 Features

- **Genetic Algorithm Implementation:** Uses crossover, mutation, and selection for evolutionary optimization.
- **Dynamic Visualization:** Plots optimal routes with `matplotlib`.
- **Balance Penalty:** Ensures fairness by penalizing uneven distribution of distances among vehicles.

---

## 📋 How It Works

1. **Random Locations:** Generates random coordinates for locations and a depot.
2. **Fitness Function:** Evaluates the total distance traveled by vehicles, including a balance penalty based on the standard deviation of distances.
3. **GA Operators:** Employs selection, crossover, and mutation to evolve solutions.
4. **Visualization:** Displays the best solution as a graphical route.

---

## 🛠️ Prerequisites

Install the required Python libraries:

```bash
pip install deap matplotlib numpy
