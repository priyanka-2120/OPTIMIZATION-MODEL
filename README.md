# OPTIMIZATION-MODEL

COMPANY:CODTECH IT SOLUTIONS

NAME:V PRIYANKA

INTERN ID:CT06WV72

DOMAIN:DATA SCIENCE

DURATION:6 WEEKS

MENTOR:NEELA SANTOSH

##Problem Setup: The chosen business problem involves a company producing two products (e.g., Product A and Product B) using constrained resources—labor hours and machine hours. Each product has a profit margin (e.g., $20 for A, $30 for B), and resource constraints are defined (e.g., 100 labor hours and 80 machine hours available). Product A requires 2 labor hours and 1 machine hour per unit, while Product B needs 1 labor hour and 2 machine hours. The goal is to determine the optimal production quantities to maximize profit while respecting resource limits.

Solution Development: The solution is implemented in a Jupyter notebook using PuLP. The optimization model is formulated as follows:

Decision Variables: Define variables for the number of units of Product A (x1) and Product B (x2) to produce, with non-negativity constraints (x1 >= 0, x2 >= 0).
Objective Function: Maximize profit, expressed as 20*x1 + 30*x2.
Constraints: Add resource limits, e.g., 2*x1 + 1*x2 <= 100 (labor) and 1*x1 + 2*x2 <= 80 (machine).
PuLP’s LpProblem class sets up the maximization problem, and constraints are added using +=. The model is solved with solve(), yielding optimal values for x1 and x2.
Results and Insights: The notebook outputs the optimal production plan (e.g., 40 units of A, 20 units of B), total profit (e.g., $1400), and resource usage. Visualizations (e.g., using Matplotlib) may plot the feasible region, constraints, and optimal point, enhancing interpretability. Insights include the trade-off between products, resource bottlenecks, and sensitivity to changes in profit margins or constraints, guiding business decisions.

Deliverable: The deliverable is a Jupyter notebook demonstrating the problem setup, PuLP implementation, solution, and insights. It includes code, explanations, and visualizations, meeting CODTECH’s requirement for an optimization model showcase. The project highlights practical application of linear programming to improve efficiency and profitability.

Tools: Python, PuLP, NumPy, and Matplotlib are used, showcasing optimization techniques in a business context.

#Output

![Image](https://github.com/user-attachments/assets/95134cb7-7d42-42e0-9f62-5f7657e1db6b)
