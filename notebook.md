# Research Notebook

## Selection Objective

Trying to design and model a light-activated self-healing polymer composite that can withstand the extreme Martian conditions and will be able to aid in repair in space habitats.

First need to decide an existing polymer for simulation testing in Martian conditions.

## Selection Priorities

Important criteria for this polymer:

- Light-activated  
- Self-healing  
- Substantial data  
- Repeat healing  
- Realistic temperatures  

## Candidate Comparison

| Polymer Name / Link | Light Trigger | State | Healing Time & Efficiency | Temp (°C) | Mechanical Strength | Repeat Healing | Radiation Notes | Other Notes |
|---------------------|---------------|-------|----------------------------|-----------|----------------------|----------------|------------------|--------------|
| [Poly(acrylate amide) Elastomers Reinforced with Polyhedral Oligomeric Silsesquioxanes](https://www.nature.com/articles/s41578-020-0202-4) | Visible light | Solid-like at high cross-linking density; viscous liquid at low shear rate | ~12 hours healing; strain: 90% at 3h, 230% at 12h (uncut 245%) | 30 | 0.6 MPa at 245% strain | Not stated | Not stated | Temperature effect not tested |
| [Ethylenediamine-Polyurea Microcapsule Epoxy](https://pubs.acs.org/doi/abs/10.1021/acsapm.8b00116) | Not specified (UV/Visible unknown) | Solid via solidification; liquid isocyanates | Mostly 72 to 144 hours; nearly full by 366h | 25 | Not specified | Not stated | Not stated | Cold or breakage behavior unknown |
| [Polyurethane Elastomers](https://www.mdpi.com/1996-1944/13/2/326) | UV light | Gel | ~12h near-complete healing | 80 | 3.39 MPa tensile strength | Yes, efficiency drops over 3 cycles: 95%, 87%, 60% | Not stated | Healing likely ineffective at low temp |
| [4,4′-Diaminodiphenyl disulfide](https://pubs.acs.org/doi/full/10.1021/acsmacrolett.9b00766) | UV light | Solid | 1–3h near-complete healing | 100 | Breaks at ~3.7 MPa stress | Yes, due to S-S bonds | Excessive UV causes weakening | Heat accelerates healing; low temp slows process |

## Selected Material and Rationale

Based on comparison between the previous 4 different light-activated self-healing polymers for a baseline for the simulation design, Poly(acrylate amide) Elastomers reinforced with Polyhedral Oligomeric Silsesquioxanes was selected. This decision was made based on the following criteria:

- Light-activated  
- Self-healing  
- Initial study provided lots of data around healing capabilities over 12 hour timeframe  
- Shows high strain tolerance up to 230% at 12 hours of healing, relevant to meteoroid damage  
- 30°C is one of the lowest temperatures tested  

However, lacked repeat healing mention so still unstated — further research to be done to confirm if or not.

## Limitations

While the selected polymer meets most of the desired criteria for simulation purposes, the following limitations should be noted:

- No clear data on radiation resistance, which is relevant for Martian surface exposure  
- No confirmation of repeat healing capability — this may impact long-term durability  
- The lowest tested temperature is 30°C; Martian night temperatures reach −60°C, so performance at lower temperatures remains unvalidated  
- Additional material tuning (e.g., hybridization, coatings, insulation) may be needed for operational use

## Martian Environmental Parameters for Simulation

A baseline of important factors of Martian conditions was found from current research (see `sources.md`), out of the provided conditions, the following conditions were selected for the Martian simulation environment:

- **Low Temperature**: -35°C
- **Oxidation**: perchlorates in soil, chemical degradation.
- **Radiation Exposure**: Estimated solar UV flux, particularly UVA/UVB relevant to photoinitiators.
- **Micrometeoroid Events**: Incorporated using probabilistic models from MRO data.

### Rationale

These factors were chosen because they are the most probable environmental conditions to effect the polymer.

# Data Input for Each Factor

## Low Temperature
- **POLYMER**
  - Glass transition temperature (Tg)
  - Tensile strength, flexibility
  - Thermal contraction coefficients
- **MARS**
  - -35°C

## Oxidation
- **POLYMER**
  - Reaction rates with perchlorates
  - Changes in properties after oxidizer exposure
  - Oxidative degradation of polymers by perchlorates

## Radiation Exposure
- **POLYMER**
  - UV absorption spectra of the polymer
  - Rate of photodegradation by UVA/UVB
- **MARS**
  - Activation efficiency of photoinitiators under Martian UV flux

## Micrometeoroid Events
- **POLYMER**
  - Self-healing response time after micrometeoroid damage
  - Damage thresholds from high-velocity impacts
- **MARS**
  - Impact frequency and energy from Mars Reconnaissance Orbiter data

