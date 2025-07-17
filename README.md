# SDRP: Self-Healing Polymers for Space Habitats

## Project Overview
In Martian environments, inflatable habitats are at risk of damage due to the extreme environmental conditions which could pose risk to the crew in such habitats. This project explores the design and simulation of a light-activated self-healing polymer composite that is able to mitigate the damage caused by Martian conditions. The simulations show the effect of the micrometeoroid damage on the polymer and the healing process triggered subsequently by light with an overall aim of net reduction damage over time in comparison to non-healing materials. This research could help with the development of advanced materials that would improve habitat durability increasing duration and safety of human missions on mars. 

## Research Question
Can I design and model a light-activated self-healing polymer composite tailored for micrometeoroid damage repair in inflatable space habitats on Mars?

## Hypothesis
It is possible to design a light-activated self-healing polymer composite which can repair micrometeoroid damage in inflatable space habitats on Mars by using simulations to predict responses to mechanical damage and its healing responses under Martian conditions.

## Simulation Assumptions

- The polymer will be modeled as a 2D grid.
- Random damage will occur at set time steps.
- When light is present, the 2D grid will begin to fill the holes (heal damage).
- The light intensity will be constant throughout the simulation.
- Mars environment parameters will be modeled as fixed constants, ignoring rare or inconsistent events.
- The control material will not heal and will accumulate damage over time.

| Polymer Name / Link | Light Trigger | State | Healing Time & Efficiency | Temp (°C) | Mechanical Strength | Repeat Healing | Radiation Notes | Other Notes |
|--------------------|---------------|-------|---------------------------|-----------|---------------------|----------------|-----------------|-------------|
| [Poly(acrylate amide) Elastomers Reinforced with Polyhedral Oligomeric Silsesquioxanes](https://www.nature.com/articles/s41578-020-0202-4) | Visible light | Solid-like at high cross-linking density; viscous liquid at low shear rate | ~12 hours healing; strain: 90% at 3h, 230% at 12h (uncut 245%) | 30 | 0.6 MPa at 245% strain | Not stated | Not stated | Temperature effect not tested |
| [Ethylenediamine-Polyurea Microcapsule Epoxy](https://pubs.acs.org/doi/abs/10.1021/acsapm.8b00116) | Not specified (UV/Visible unknown) | Solid via solidification; liquid isocyanates | Mostly 72 to 144 hours; nearly full by 366h | 25 | Not specified | Not stated | Not stated | Cold or breakage behavior unknown |
| [Polyurethane Elastomers](https://www.mdpi.com/1996-1944/13/2/326) | UV light | Gel | ~12h near-complete healing | 80 | 3.39 MPa tensile strength | Yes, efficiency drops over 3 cycles: 95%, 87%, 60% | Not stated | Healing likely ineffective at low temp |
| [4,4′-Diaminodiphenyl disulfide](https://pubs.acs.org/doi/full/10.1021/acsmacrolett.9b00766) | UV light | Solid | 1–3h near-complete healing | 100 | Breaks at ~3.7 MPa stress | Yes, due to S-S bonds | Excessive UV causes weakening | Heat accelerates healing; low temp slows process |

## Chosen inital polymer simulation
Based on comparison between 4 different light-activated self-healing polymers for a baseline for the simulation design, Poly(acrylate amide) Elastomers reinforced with Polyhedral Oligomeric Silsesquioxanes was selected. This decision was made based on the following criteria:
- shows high strain tolerance up to 230% at 12 hours of healing relevant to meteoroid damage.
- initial study provided lots of data around healing capabilities over 12 hour timeframe.

## Documentation
- Hypothesis
- Background Research
- Methodology
- Simulation
- Results

## Tools
- Materials Studio (academic license/free trial)
- Python + ASE (Atomic Simulation Environment)
- LAMMPS / GROMACS for molecular dynamics
- COMSOL (for Finite Element Analysis simulations)
- MATLAB for modelling (if available)

## Deliverables
- GitHub repository with all code and documentation
- Full PDF report or blog post (to be linked on LinkedIn)
- Visual diagrams and models
