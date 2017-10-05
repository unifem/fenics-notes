# FEniCS Notes

This repository contains a collection of nots on FEniCS using Jupyter Notebooks, which teach how to use finite element methods to solve PDEs and to solve difficult linear systems from PDE discretizations using FEniCS. These notes will cover the following:
 - Fundamentals of finite element methods
 - Modeling linear and nonlinear elasticity
 - Solving the heat equation
 - Solving incompressible Navier-Stokes equations
 - Generating meshes
 - Specifying boundary conditions
 - Controlling iterative solvers
 - Fluid-structure interaction
 - Multigrid methods

Most of the materials were borrowed from [the FEniCS Tutorial](https://fenicsproject.org/tutorial/) and [the FEniCS Book](https://fenicsproject.org/book/). However, they have been rearranged and expanded for teaching an FEM course and for FEM research at Stony Brook University. 

To study the Notebooks, here is the recommended sequence:
 1. [Fundamentals - Poisson equations](notebooks/poisson.ipynb)
    - [Case study: deflection of a membrane using Poisson equations](notebooks/poisson_membrane.ipynb)
 2. [Modeling linear elasticity](notebooks/elasticity.ipynb)
 3. [Solving the heat equation](notebooks/heat-equation.ipynb)
 4. [Solving incompressible Navier-Stokes equations](notebooks/navier_stokes.ipynb)
    - [Case study: Navier-Stokes for a cylinder](notebooks/navier_stokes_cylinder.ipynb)

To run these notebooks interactively, use the ams529_jupyter.py script at https://github.com/compdatasci/ams529-desktop.
