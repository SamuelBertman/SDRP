# SDRP: Light-Activated Self-Healing Polymers for Martian Habitats

## Executive Summary
Designing the future of Martian habitats demands materials that *self-heal* under harsh space conditions to ensure safety during long-term missons. This project develops and simulates a **novel light-activated self-healing polymer composite**, engineered to autonomously repair micrometeoroid damage, radiation-induced defects, and thermal cycling stress in inflatable habitats on Mars. My work pushes the boundaries of aerospace materials science by delivering a polymer system that *increases habitat durability, mission duration, and crew safety*, this project addresses a critical bottleneck in a long-term human presence on Mars.

## Scientific Objective
- model, design and validate a **polymer composite capable of repeated autonomous self-healing** triggered by light exposure under Martian environmental parameters.
- Quantify damage accumulation and healing kinetics under simulated micrometeoroid impact, radiation, and extreme thermal gradients.
- Demonstrate net durability gain compared to non-healing polymers, setting precedence of design rules for next-gen aerospace materials.

## Strategic Significance
- First computational model integrating **molecular dynamics, finite element analysis, and environment-driven light activation** in a Mars habitat polymer composite.
- Addresses a significant aerospace materials challenge: **extending operational life of inflatable space structures with minimal maintenance**.
- Generates predictive frameworks to accelerate experimental validation and aerospace qualification.

## Simulations to be Run
### UV - LAMMPS or GROMACS molecular dynamics with photon-coupled modules using a flux of 2-7x
. chain scission (ϕ) over time
. damage parameter (D)
. crosslink density (ν)
### Thermal cycling - COMSOL multiphysics, molecular dynamics for chain mobility
. chain scission (thermally-induced)
. crosslink evolution
. healing efficiency under temperature cycles
### Stress + creep - python + ASE lattice model + Maxwell/Voigt/Kelvin viscoelastic models
. strain (ε) vs time
. creep stages
. stress recovery 
. D evolution
### Oxidation - ReaxFF molecular dynamics
. ϕ (oxidation-induced)
. modulus reduction
. D evolution
### Micrometeoroid impacts - LAMMPS or GROMACS
. localised ϕ
. structural damage zones
. D vs time
### Healing - molecular dynamics
. healing efficiency
. time for full/partial recovery
. repeatability

## FEA laminate simulations
### . using COMSOL multiphysics
parameters: healing kinetics v(t), D: UV stress thermal oxidation, effective elastic modulus, creep properties
environmental conditions: ~10⁻⁵ mbar (vacuum), thermal swings, combined UV mechanical and thermal loading, micrometeoroid flux
layers: bladder + restraint layers (where self-healing PU is), microcapsules for extrinsic healing (structural-level add-on), nanofiller reinforcement, external barrier layer (for gas retention)
outputs: stress-strain curves over repeated damage-heal cycles, spatial damage maps, net durability gain vs non-healing laminate, optimal placement/density of microcapsules and nanofillers

## Deliverables
- **Fully documented simulation codebase** with modular, extensible architecture.
- **Comprehensive report (PDF + blog post)** detailing methodology, results, and aerospace implications.
- **Visual models and plots** demonstrating damage accumulation and healing progression.
- Ongoing GitHub updates reflecting continuous integration of new data and models.

---

## Next Steps
- Expand model complexity to 3D polymer networks.
- Integrate variable light intensity and stochastic Martian weather effects.
- Collaborate with experimental groups to validate simulation predictions.

---

*This project is a strategic step toward revolutionizing materials for sustainable human life on Mars.*
