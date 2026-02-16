
--Author----
Seyi Samuel Obafemi, PhD
Geoscientist | Computational Fluid Dynamics | Process-Based Modeling
Missouri University of Science & Technology

Hi, my name is Seyi, I build rapid Multiphysics CFD Platforms for novel sediment transport & subsurface-coupled flow.

---Repository Overview-----

This repository contains a research-grade multiphysics computational fluid dynamics (CFD) framework integrating:

1. Lattice Boltzmann Method (LBM) for incompressible Navier–Stokes flow

2. Exner equation coupling for morphodynamic bed evolution

3. Sediment transport dynamics under subcritical and supercritical flow regimes

4. Parameter sensitivity analysis for slope, Froude number, Reynolds number, and transport efficiency

5. Gravity-current simulations (lock-exchange setup)

7. River and coastal morphodynamics

8. Subsurface-connected sediment routing systems

9. Energy-transition applications (sediment transport, reservoir-scale flow processes)

----Scientific Relevance-----

This framework bridges:

CFD (Navier–Stokes solvers)

Sediment transport physics

Multiphysics coupling

Geomorphodynamics

Subsurface flow modeling concepts

It supports research relevant to:

Coastal and ocean flows

Reservoir-scale transport

Energy transition (e.g., CO₂ sequestration transport processes)

Petrophysical-scale transport analog modeling

---Numerical Capabilities------

1. D2Q9 / D3Q19 LBM solver

2. Explicit Exner-type bed evolution coupling

3. Stability-controlled time stepping

4. Parameter sweep capability

5. Structured grid finite-difference style discretization

6. Designed for extension to MPI/HPC workflows

---- Key Features--------

Fully coupled flow–morphodynamics solver

Supports subcritical and supercritical regimes (Froude-controlled)

Captures erosion, deposition, and bed aggradation

Modular structure for extension to:

Turbulence closures

Multiphase transport

Reduced Order Modeling

Machine Learning coupling

---Requirements------

Python ≥ 3.10, NumPy, SciPy, Matplotlib

-----Install dependencies-----

pip install -r requirements.txt


------Outputs--------------

Velocity fields (u, v)

Bed elevation evolution

Deposition thickness

Diagnostic metrics

----Research Extensions (Ongoing Work)-------

HPC parallelization (MPI-ready structure)

Physics-informed neural network integration

Reduced Order Modeling (ROM)

Subsurface multiphase coupling concepts



High-performance scientific computing

AI-assisted physical simulation
