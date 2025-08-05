# SDRP: Self-Healing Polymers for Space Habitats

## Project Overview
In Martian environments, inflatable habitats are at risk of damage due to the extreme environmental conditions which could pose risk to the crew in such habitats. This project explores the design and simulation of a light-activated self-healing polymer composite that is able to mitigate the damage caused by Martian conditions. The simulations show the effect of the micrometeoroid damage, radiation and severe temperature swings on the polymer and the healing process triggered subsequently by light with an overall aim of net reduction damage over time in comparison to non-healing materials. This research could help with the development of advanced materials that would improve habitat durability increasing duration and safety of human missions on mars. 

## Research Question
Can I design and model a light-activated self-healing polymer composite tailored for damage repair in inflatable space habitats on Mars?

## Hypothesis
It is possible to design a light-activated self-healing polymer composite which can repair damage in inflatable space habitats on Mars by using simulations to predict responses to mechanical damage and its healing responses under Martian conditions.

## Tools (to be used)
- Materials Studio (academic license/free trial)
- Python + ASE (Atomic Simulation Environment)
- LAMMPS / GROMACS for molecular dynamics
- COMSOL (for Finite Element Analysis simulations)
- MATLAB for modelling (if available)

## Folder Structure
- **assets/** contains images like `polymer_healing_mechanism.png` to visually explain key concepts.
- **data/** stores CSV files such as `control_damage.csv` and `healing_damage.csv` with simulation results.
- **report/** includes `background_research.md` and other documentation related to literature and project reports.
- **results/plots/** holds plot images (`comparison.png`, `healing_sim.png`) that showcase simulation outcomes.
- **simulation/** contains Python scripts like `healing_model.py`, `control_model.py`, and `martian_env.py` that implement the damage and healing simulations.
- **sources.md** lists references and additional source material beyond the formal literature review.
- Other important files:
  - `.gitignore` excludes unnecessary files from the repository.
  - `LICENSE` contains the project’s licensing information.
  - `README.md` provides an overview and instructions.
  - `requirements.txt` lists the Python packages needed to run the simulations.

## Simulation Assumptions
- The polymer will be modeled as a 2D grid.
- Random damage will occur at set time steps.
- When light is present, the 2D grid will begin to fill the holes (heal damage).
- The light intensity will be constant throughout the simulation.
- Mars environment parameters will be modeled as fixed constants, ignoring rare or inconsistent events.
- The control material will not heal and will accumulate damage over time.

## Results (to be documented)

## Deliverables
- GitHub repository with all code and documentation
- Full PDF report or blog post (to be linked on LinkedIn)
- Visual diagrams and models

## Link to PDF Report (to be done)
