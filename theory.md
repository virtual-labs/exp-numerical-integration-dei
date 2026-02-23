## Theory

### Introduction

Numerical integration is a computational technique used to approximate the definite integral of a function when an analytical solution is difficult or impossible to obtain. In many practical problems, especially in scientific experiments and numerical simulations, function values are available only at discrete points. Numerical integration enables the estimation of the area under a curve using these discrete data points.

### Principle of Numerical Integration
The basic principle of numerical integration is to divide the interval of integration, from the lower limit 𝑎 to the upper limit 𝑏, into a finite number of smaller sub-intervals of equal width. If the interval is divided into 𝑛 sub-intervals, the step size ℎ is given by

<img width="92" height="44" alt="image" src="https://github.com/user-attachments/assets/3512f263-1ea4-45ba-ad9f-83c42777cb57" />

Over each sub-interval, the function is approximated using simple geometric shapes whose areas can be easily calculated. The total area under the curve is then obtained by summing the areas of these shapes.

### Trapezoidal Rule
In the Trapezoidal Rule, the curve between two consecutive data points is approximated by a straight line, forming a trapezoid. The area under the curve is estimated by summing the areas of all trapezoids formed over the sub-intervals.

The Trapezoidal Rule is mathematically expressed as:

<img width="500" height="83" alt="image" src="https://github.com/user-attachments/assets/4948f325-4ce4-431e-b5ed-5f7e589b0dd7" />

This method is simple to implement and provides good accuracy for functions that do not change rapidly over the integration interval.

### Simpson’s Rule

Simpson’s Rule improves upon the Trapezoidal Rule by approximating the function using parabolic curves instead of straight lines. This method requires the number of sub-intervals to be even and uses quadratic interpolation to estimate the area under the curve.

The mathematical expression for Simpson’s Rule is:

<img width="688" height="83" alt="image" src="https://github.com/user-attachments/assets/9ad623bd-2a6c-4d82-aee1-34001a500014" />

Due to its higher-order approximation, Simpson’s Rule generally provides more accurate results for smooth and continuous functions.

### Accuracy and Step Size Considerations
The accuracy of numerical integration depends on the number of sub-intervals and the step size ℎ . A smaller step size generally leads to better accuracy but increases computational effort. Choosing an appropriate step size is therefore essential for reliable integration results.

### Applications of Numerical Integration
Numerical integration is widely used in physics, engineering, computer science, and environmental studies. Common applications include calculating displacement from velocity data, estimating work and energy, determining areas and volumes, and analyzing experimental and measured datasets where analytical integration is not feasible.


