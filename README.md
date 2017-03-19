# FEniCS Notes

This repository contains a collection of nots on FEniCS using Jupyter Notebooks, which teach how to use finite element methods to solve PDEs and to solve difficult linear systems from PDE discretizations using FEniCS. These Notes will teach you the following:
 - Fundamentals of finite element methods
 - Modeling linear and nonlinear elasticity
 - Solving incompressible Navier-stokes equations
 - Generating meshes
 - Specifying boundary conditions
 - Selecting iterative solvers linear systems from FEniCS
 - Fluid-structure interaction
 - Multigrid methods
 - Topology optimization

Most of the materials were borrowed from [the FEniCS Tutorial](https://fenicsproject.org/tutorial/) and [the FEniCS Book](https://fenicsproject.org/book/). However, they have been rearranged and expanded for teaching a FEM course and for the research in the NumGeom Group at Stony Brook University. 

To study the Notebooks, here is the recommended sequence:
 1. [Fundamentals - Poisson equations](notebooks/poisson.ipynb)
    - [Case study: deflection of a membrane using Poisson equations](notebooks/poisson_membrane.ipynb)
 2. [Modeling linear elasticity](notebooks/elasticity.ipynb)
    - Case study (TODO)
 3. [Solving Navier-Stokes equations](notebooks/navier_stokes.ipynb)
    - [Case study: Navier-Stokes for a cylinder](notebooks/navier_stokes_cylinder.ipynb)

To run these notebooks interactively, you need to set up some software packages on your computer. First, install Docker for your platform (Windows, MacOS, Linux, cloud platforms, etc.), follow the instructions at [docker.com](https://docs.docker.com/engine/getstarted/step_one/). Then, download this repository and start Jupyter Notebook using the command `docker-notebook` script in the directory. For example, to open notebooks/poisson.ipynb, use the command:
```
    ./docker-notebook notebooks/poisson.ipynb
```
