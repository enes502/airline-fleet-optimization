# ✈️ Airline Fleet & Route Optimization (MILP)

A powerful optimization model built with **Python** and the **PuLP** library, designed to solve Mixed-Integer Linear Programming (MILP) problems for commercial airline operations. The system optimizes aircraft deployment across multiple periods and destinations to maximize total profit while adhering to strict operational, fuel, landing, and passenger demand constraints.

---

## 🚀 Features

*   **Integer Programming Variables:** Manages discrete aircraft allocation variables across various aircraft models (A220, A320, A330, A340, A350), periods, and destination locations.
*   **Profit Maximization Objective:** Calculates net profit by balancing ticket revenues against operational costs, fuel expenses, and airport landing fees.
*   **Fleet Constraints:** Enforces availability limits and scheduling bounds for each aircraft type across operational periods (January, April, July, October).
*   **Resource Budgeting:** Implements upper-bound constraints for fuel consumption and airport landing budgets per period.
*   **Demand Satisfaction:** Ensures passenger demand requirements are met across all destinations.
*   **Solver Diagnostics:** Integrates automatic status checking, objective value reporting, and constraint slack analysis using CBC.

---

## 📂 Project Structure

```text
├── airline_optimizer.py   # Main MILP model, objective function, constraints, and solver script
└── README.md              # Project documentation

python airline_optimizer.py
