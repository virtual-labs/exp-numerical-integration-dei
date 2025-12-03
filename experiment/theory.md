### Theory

Numerical integration is a computational technique used to approximate the area under a curve when the exact integral is unknown or difficult to compute analytically. Instead of relying on symbolic calculus, the method uses discrete data points from a function and calculates the sum of small segment areas to estimate the total integral value.

In numerical integration, the interval between the lower and upper limits is divided into smaller segments. Each segment is then used to construct a simple geometric shape whose area can be calculated easily. Adding these small areas together provides an estimate of the region under the curve.

Two commonly used numerical integration methods include:

1. **Trapezoidal Rule**  
   This method connects data points with straight lines, forming trapezoids. The total area is found by summing the areas of all trapezoids. It is simple to apply and works effectively for functions that do not vary rapidly.

2. **Simpson’s Rule**  
   This method uses parabolic curves to approximate the shape of the function between data points. By applying quadratic interpolation, Simpson’s Rule generally provides higher accuracy compared to the Trapezoidal Rule, especially for smooth and continuous functions.

Numerical integration is widely used in physics, engineering, computer science, environmental analysis, and many other real-world applications where complex functions or experimental data make traditional calculus challenging. It enables precise estimation of quantities such as distance, energy, volume, and probability distributions, even when exact solutions are not feasible.
