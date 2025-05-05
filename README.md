Proximal Gradient Descent with Nesterov Momentum under PL Inequality
- Overview
This project introduces a new optimization algorithm called Proximal Gradient Descent with Nesterov Momentum for solving problems with weakly smooth objectives. The algorithm is designed to work efficiently under the Polyak–Łojasiewicz (PL) inequality , which ensures convergence to the optimal solution.

- Key Features
  - Handles Weak Smoothness : The algorithm works well even when the objective function has gradients that change at varying rates.
  - Supports Non-Smooth Terms : It can handle optimization problems where part of the objective function is not smooth or differentiable.
  - Accelerates Convergence : Nesterov momentum is used to speed up the optimization process by leveraging past updates.
  - Guaranteed Convergence : Under the PL inequality, the algorithm is guaranteed to converge to the optimal solution.
- How It Works
The algorithm alternates between two main steps:

  - Momentum Update : A momentum term is computed to incorporate information from previous iterations, helping the algorithm move more efficiently toward the solution.
  - Proximal Update : A proximal operator is applied to handle non-smooth parts of the objective function, ensuring the solution remains feasible.
By combining these steps, the algorithm achieves faster convergence while maintaining robustness for challenging optimization problems.

- Why Use This Algorithm?
This approach is particularly useful for problems where:

  - The objective function has both smooth and non-smooth components.
  - Gradients are not perfectly smooth but still follow certain continuity properties.
  - You need a reliable method with theoretical guarantees for convergence.
- Results
The algorithm has been shown to converge efficiently under the PL inequality. Experiments demonstrate its ability to find optimal solutions faster than traditional methods in weakly smooth settings.

- Getting Started
To use this algorithm:

  - Define your objective function, including both smooth and non-smooth parts.
  - Set parameters such as the step size and momentum coefficient.
  - Run the algorithm and observe the convergence behavior.
- Acknowledgments
This work builds on foundational ideas from proximal gradient methods, Nesterov acceleration, and the Polyak–Łojasiewicz inequality. Special thanks to researchers who have contributed to these areas.
