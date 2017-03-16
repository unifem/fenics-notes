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

To get started, you need to set up some software packages.
 1. Set up FEniCS and Jupyter Notebook by following the instructions [here](https://github.com/numgeom/notes/wiki/Installing-FEniCS).
 2. Install additional mesh generation packages [`PyGmesh`](https://github.com/numgeom/notes/wiki/Mesh-Generation-Packages-in-Python#python-front-end-of-gmsh-pygmsh) and [`MeshPy`](https://github.com/numgeom/notes/wiki/Mesh-Generation-Packages-in-Python#python-front-end-of-triangle-and-tetgen-meshpy).
 3. For proper rendering of LaTeX environments in the Jupyter Notebook, install `jupyter_latex_envs` by following the instructions [here](https://github.com/numgeom/notes/wiki/Installation-Guides-for-Jupyter-Notebooks#latex-environments-jupyter_latex_envs).
 4. For professional 3-D visualization, download and install [ParaView](http://www.paraview.org/download/).

To study the Notebooks, here is the recommended sequence:
 1. [Fundamentals - Poisson equations](notebooks/poisson.ipynb)
    - [Case study: deflection of a membrane using Poisson equations](notebooks/poisson_membrane.ipynb)
 2. [Modeling linear elasticity](notebooks/elasticity.ipynb)
    - Case study (TODO)
 3. [Solving Navier-Stokes equations](notebooks/navier_stokes.ipynb)
    - [Case study: Navier-Stokes for a cylinder](notebooks/navier_stokes_cylinder.ipynb)
