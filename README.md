## Overview

This repository contains some of the code I wrote for the development of a one-dimensional Density Functional Theory (DFT) engine. The solver is designed to compute the electron density and observables of the many-electron 1D infinite potential well using a Jacobi polynomial basis within a self-consistent cycle. The code also includes a multi-grid Poisson solver to compute the Hartree potential.

## Features

- Kohn-Sham method implementation for solving electron structure problems
- Numerical solutions for the Schrödinger equation using a Jacobi-Legendre basis set
- Poisson solver for the Hartree potential using a multi-grid approach
- Use of the density matrix for computing system observables (e.g., kinetic energy contributions)
- Efficient computation using Python with NumPy, SciPy, and Matplotlib

## Future Work

- Implement exchange-correlation functionals beyond $v_{\text{xc}}\[n\](x)=Un(x)$, where $U$ is a positive constant and $n(x)$ is the electron density
- Optimize numerical techniques for improved convergence
- Extend to more complex systems such as solving the radial equation for the atom

## Author
Daniel Barron
