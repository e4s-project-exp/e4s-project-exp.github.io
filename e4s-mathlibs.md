---
layout: single
title: "Math Libraries"
permalink: /e4s-mathlibs/
classes: wide
sidebar:
  nav: "productfamiliesmenu"
---

### Placeholder text - needs improvement

This product family supplies reusable building blocks for computational simulation and modeling: linear and nonlinear solvers, time integrators, preconditioners, eigensolvers, optimization, and related tools.

### Core libraries/tools  
- **PETSc** (and its optimization/TAO extensions) for scalable solvers, time stepping, nonlinear systems   
- **Trilinos** (and its many packages) for solver, discretization, preconditioning, multilevel, and modeling support   
- Sparse direct solvers such as **SuperLU**
- ODE/DAE solvers such as **SUNDIALS**
- Related linear algebra and kernel libraries (e.g. KokkosKernels, MAGMA, hypre) that often interoperate with solver frameworks

### Application needs addressed  
- Efficient and scalable solution of large sparse linear (and nonlinear) systems arising from PDE discretizations  
- Time-dependent or transient simulation (via ODE/DAE integrators)  
- Eigenvalue problems, matrix factorizations, preconditioner construction  
- Coupled multiphysics and optimization problems, which reuse solver abstractions  
- Flexibility in solver configuration (e.g. switching preconditioners, using mixed precision, block or batched solves)  


Copyright © E4S a Series of LF Projects, LLC For web site terms of use, trademark policy and other project policies please see <https://lfprojects.org>.
