# Gradient-Descent


This code utilizes **Stochastic Gradient Descent (SGD)** to solve a cubic equation **ax^3 + bx^2 + cx + d**. It initializes a random value for x and updates it over a number of iterations using the gradient of the cubic equation with respect to x. The gradient is computed and then passed through a **rectified linear unit (ReLU)** function to ensure it's positive or zero, which helps prevent negative updates. The learning rate controls the size of each update, and the process repeats for a specified number of iterations (n) to converge towards a solution for x that minimizes the cubic equation. The final value of x after the iterations represents the solution for the cubic equation
