# Quantum Reservoir Simulation for Geothermal & CO₂ Sequestration

This project is licensed under the MIT License.

---

## Overview

This repository presents a **PoC** exploring how hybrid quantum–classical algorithms could assist in planning **geothermal energy systems and carbon capture & sequestration (CCS) infrastructure**.

Subsurface reservoir planning involves complex **multiphysics simulations and large-scale optimization problems**, including:

* CO₂ source–sink allocation
* pipeline routing
* reservoir capacity planning
* uncertainty quantification
* injection strategy optimization

These problems can involve **millions of variables** when realistic industrial scenarios are considered. Classical high-performance computing (HPC) approaches provide approximate solutions but face scaling challenges for large scenario exploration.

This project explores how **variational quantum algorithms (VQAs)** and hybrid optimization methods could complement classical simulation pipelines.

---

## Sustainable Development Goals

This use case contributes to several UN Sustainable Development Goals:

* **SDG 7 – Affordable and Clean Energy**
  Geothermal energy provides stable renewable baseload power.

* **SDG 9 – Industry, Innovation and Infrastructure**
  CCS infrastructure supports decarbonization of heavy industry.

* **SDG 13 – Climate Action**
  Carbon sequestration is a key pathway for achieving net-zero emissions.

---

## Repository Goals

The repository provides a **minimal research prototype** demonstrating:

1. Representation of a CCS source–sink network
2. Construction of a reservoir allocation optimization problem
3. Mapping the problem into a **QUBO formulation**
4. Solving the optimization using **Quantum Approximate Optimization Algorithm (QAOA)**
5. Comparison with classical optimization baselines

The objective is **not to replace classical reservoir simulators**, but to explore how **quantum optimization layers** may accelerate decision-making in large scenario spaces.

---

## Research Context

Reservoir modeling is a canonical **multiphysics simulation challenge** involving:

* nonlinear PDE systems
* uncertainty quantification
* large-scale parameter inversion
* stochastic scenario exploration

Quantum computing may offer advantages in:

* combinatorial optimization
* Monte Carlo sampling
* linear system solving

These capabilities could support next-generation **climate infrastructure planning tools**.

---

## Potential Impact

If successful, hybrid quantum workflows could:

* accelerate CCS project planning
* reduce infrastructure design costs
* improve reservoir utilization strategies
* support rapid exploration of policy and investment scenarios

Such capabilities are critical for **large-scale deployment of decarbonization infrastructure**.

---

## Limitations

This repository is a **research demonstrator**.

The current implementation:

* uses synthetic datasets
* simplifies reservoir physics
* focuses on optimization layers rather than full multiphysics simulation

Future work would require collaboration with:

* geoscientists
* reservoir engineers
* HPC simulation experts

---

## Future Work

Planned extensions include:

* integration with real geological datasets
* hybrid HPC–quantum simulation pipelines
* large-scale QUBO formulations
* uncertainty-aware optimization
* benchmarking across quantum hardware platforms
