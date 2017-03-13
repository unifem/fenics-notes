# FEniCS Notes

This repository contains a collection of Jupyter Notebooks, which teaches how to use finite element methods to solve PDEs and to solve difficult linear systems from PDE discretizations using FEniCS. These Notes will teach you the following:
 - Fundamentals of finite element methods
 - Modeling linear and nonlinear elasticity
 - Solving incompressible Navier-stokes equations
 - Generating complicated meshes for FEniCS and specifying boundary conditions
 - Selecting iterative solvers linear systems from FEniCS
 - Fluid-structure interaction
 - Multigrid methods
 - Topology optimization

Most of the materials were borrowed from [the FEniCS Tutorial](https://fenicsproject.org/tutorial/) and [the FEniCS Book](https://fenicsproject.org/book/). However, they have been rearranged and expanded for teaching a FEM course and for the research in the NumGeom Group at Stony Brook University. 

To get started, you need to set up a few software packages. It is relatively simple and painless:
 1. Set up FEniCS and Jupyter Notebook by following the instructions [here](../../wiki/Setup-Jupyter-Notebook-to-Use-FEniCS-Notes).
 2. For proper rendering of LaTeX equations and theorems in the Jupyter Notebook, install `jupyter_latex_envs` by following the instructions [here](
https://github.com/numgeom/fenics-notes/wiki/Useful-Addons-for-Jupyter-Notebook#latex-environments-jupyter_latex_envs).
 3. For professional 3-D visualization, you are highly recommended to install [ParaView](http://www.paraview.org/), which you can download at <http://www.paraview.org/download/>.

To study the Notebooks, here is the recommended sequence:
 1. [Fundamentals - Poisson equations](notebooks/poisson.ipynb)
    - [Case study: deflection of a membrane using Poisson equations](notebooks/poisson_membrane.ipynb)
 2. [Modeling linear elasticity](notebooks/elasticity.ipynb)
    - Case study (TODO)
 3. [Solving Navier-Stokes equations](notebooks/navier_stokes.ipynb)
    - [Case study: Navier-Stokes for a cylinder](notebooks/navier_stokes_cylinder.ipynb)
