

In this project, we are tasked to calculate the total energy of interactions of two identical cubes that are oriented such that their corresponding edges are parallel to the coordinate axes and are displaced with respect to each other along the X-axis. The cubes are charged with a non-uniform charge density and are separated by distance r. 

To do so, we needed to compute a six dimensional integrator for each of the 3 local coordinates of the cube. 3 different methods were used to compute the integral:

* GSL VEGAS (Monte Carlo Integrator) – Purple line
* Homemade Integrator – Green line
* Dipole Approximation – Blue line
