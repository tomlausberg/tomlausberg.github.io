---
permalink: /projects/
title: "Projects"
layout: archive
author_profile: true
---

# Projects



## Theses / Publications

### Master Thesis: Multi-period Optimal Power Flow with Physics-informed Graph Neural Network, 2024

#### Description

1: Designed and implemented and physics-informed graph neural network to solve the multi-period optimal power flow problem with unit commitment. Showed promising results on small grids when compared to traditional solvers.

2: I developed a physics-informed graph neural network to solve the combined Unit Commitment and Optimal Power Flow (UC-OPF) problem in power systems. The OPF problem involves finding the most economical way to meet power demand while satisfying system constraints, but its non-linear and non-convex nature makes it computationally challenging. Adding unit commitment, deciding which generators to activate, introduces integer variables that further complicate the optimization. When tested on small-scale power grids, my approach demonstrated promising accuracy and significant potential for computational speedup compared to traditional optimization methods. 

#### Technologies:

- Python, PyTorch, Torch Geometric, Gurobi, Matpower

#### Tags:

- Physics informed machine learning
- Graph Neural Networks
- Optimal Power Flow
- Unit Commitment
- Mixed Integer Optimization

### Bachelor Thesis: An Efficient Boundary-Respecting Streamfunction-Vorticity Solver, 2021

1: Developed a novel numerical solver for 2D fluid dynamics using streamfunction-vorticity formulation and discrete exterior calculus, reducing numerical dissipation common in computer graphics applications. Implemented support for non-uniform grids and parametrized viscosity for diverse fluid simulation

2: I developed a novel numerical method for solving two-dimensional fluid dynamics that significantly reduces artificial dissipation, a common problem in computer graphics fluid simulations. By reformulating the Navier-Stokes equations using streamfunction-vorticity and working in a divergence-free space, I eliminated the dissipative projection step typically required in traditional pressure-velocity solvers. The method uses discrete exterior calculus for robust numerical discretization on non-uniform grids, and includes a parametrized viscosity term to simulate diverse fluid behaviors. This approach offers improved accuracy and flexibility compared to conventional fluid simulation techniques in computer graphics.

#### Technologies:

- C++ / Eigen

#### Tags:

-  Fluid Dynamics
- Discrete Exterior Calculus
- TODO: FDM??



### Conference Paper: Low-Cost Sensor Node for Air Quality Monitoring, 2021

1: Implemented the software infrastructure for a mobile air quality monitoring system, including MicroPython-based sensor control, LoRa/LTE telemetry, and ThingsBoard-based data visualization platform

2: I developed the core software and telemetry infrastructure for a novel mobile air quality monitoring system. Using MicroPython, I implemented the sensor node's control and data acquisition functionalities for a comprehensive array of environmental sensors. I designed a hybrid communication system that leverages both LoRa and LTE networks to ensure reliable data transmission to a ThingsBoard IoT platform. To make the collected data actionable, I architected the database structure and created customized dashboards in ThingsBoard for real-time visualization and analysis of air quality parameters. The system enables cost-effective, mobile monitoring of multiple pollutants including NO2, O3, CO, and particulate matter across urban environments.



#### Technologies:

- MicroPython,  LoRaWAN, MQTT, Thingsboard

#### Tags:

- Internet Of Things
- Air quality monitoring
- Sensor Nodes



### Semester Thesis: Accuracy and Reliability of Atmospheric Correction for Optical Satellite Images, 2024

1: Evaluated the performance of atmospheric correction algorithms for Sentinel-2 satellite imagery, analyzing sen2cor and its variants to improve the conversion of top-of-atmosphere measurements to surface reflectance values.

2: I conducted a comprehensive assessment of atmospheric correction methods for Sentinel-2 satellite imagery, focusing on the sen2cor algorithm's ability to convert top-of-atmosphere measurements into accurate surface reflectance values. The research evaluated multiple variants of the algorithm under diverse conditions to determine their effectiveness in atmospheric correctionâ€”a critical step in satellite image processing. Through systematic analysis, I assessed how different modifications to sen2cor impacted the accuracy and reliability of surface reflectance retrieval, providing valuable insights for improving earth observation data processing.



#### Technologies:

- Python, rasterio/gdal/geopandas, Scikit-learn

#### Tags:

- Atmospheric Correction
- Remote Sensing
- Land Cover Classification

### ## Other Projects

### Personal Project: Finot

Time Management / Expense Tracking Website

#### Technologies:

- Python, Django, React

### Student Project: HDBSCAN Implementation

Clustering, Cache Optimization, Scalability Analysis

#### Technologies:

- C, Assembly



### Student Project: FLIP-Solver

Fluid Dynamics, Fluid Implicit Particle Solver

#### Technologies:

- C++/Eigen, Paraview



### Student Project: Comparison of High Performance Python Libraries

Python, Accerated Computing, Stencil Computations

#### Technologies:

- Python: Legate, JAX, Bohrium, GT4Py

```