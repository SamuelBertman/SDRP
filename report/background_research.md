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

## Martian Environmental Parameters for Simulation (Amils et al., 2007)

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

# Mechanics of light-activated self-healing polymer networks (Yu, Xin, & Wang, 2019)
## Healing Mechanism Overview
The light propagation through the material matrix triggers the production of free radicals that facilitate the interfacial self-healing process. Polymer chains diffuse across the interface and re-form the dynamic bonds assisted by the free radicals. The interfacial self-healing strength of the polymer increases with the light illumination time until reaching a plateau.

## Different ways they function
Relying on encapsulates of curing agents or various dynamic bonds activate the interfacial bridging mechanism when the fractured interfaces are brought into contact. External visible or ultraviolet (UV) light activates the self-healing reaction around the fracture interface.

## Photophores (the light-trigger)
“Photophore” is incorporated within the polymer network, photo-responsive chemical group. Light-triggered free radicals will activate the photophore to facilitate the polymer-chain rebinding. Two types of photophores exist — organic and inorganic, organic contain organic chemical groups, inorganic have metal-organic frameworks and nanoparticles/sheets.

## Unknowns and Challenges in Modeling
How to model the light-activated interfacial self-healing behavior remains elusive. How the light activates the photophores during the self-healing process remains unknown. How the light-triggered free radicals activate the polymer chain evolution around the healing interface remains unclear. And how the light properties including intensity and wavelength affect the self-healing performance is also ambiguous.

## Polymer used (light-activated self-healing)
Optically healable TiO2 nanocomposite hydrogels

# self-healing polyurethane based on dynamic covalent bonds (An et al., 2023)
Dynamic Bond Benefit
Dynamic covalent bonding used to maintain mechanical stress whilst self healing

## Material Focus
Polyurethane was the focus material

## Types of Self-Healing in Polyurethane
Two types of self healing around PU, extrinsic and intrinsic, extrinsic is the introduction of dynamic reversible structures (dynamic covalent bonds + non dynamic covalent interactions).

## Healing Reaction
Dynamic covalent bonds require 4 reaction steps to heal - reversible cycloaddition, exchange reactions, stable free radical mediated reshuffling and heterocyclic compound facilitated bond reformations.

## Temperature Considerations
Can be low temperature reactions for self healing but not sufficient mechanical stability.

## Need for Multi-Network Systems
Single dynamic covalent network polymers no longer sufficient, multi-network required (have high self healing and mechanical strength retainability)

## Nanofiller Addition
Nano fillers can be added to improve interaction for healing

# Self-healing waterborne polyurethane - matrix for preparing nano composite coating h-BN/GO/NiO (Kianfar et al., 2024)
Properties
Self-healing waterborne polyurethane - matrix for preparing nano composite coating h-BN/GO/NiO. SBWPU containing 20% of healing agent showed anti-corrosion properties. Gradually loose function from physical damage.

## Enhancing Base Properties
Introducing covalent structures into waterborne polyurethane increases mechanical stability + lifetime. External stimuli such as light triggers reversible covalent bonds in polymer networks forming new bonds. Introducing Diimine-DiOH produces good mechanical strength coating polymer WPU.

## Importance of Aromatic Schiff Base
Focus on Aromatic Schiff base compounds are easily synthesised, good self healing, work through visible light, and rigid structure so high mechanical performance. Polyurethane on its own has low mechanical strength but with specific amounts of aromatic Schiff base groups could increase this in addition to 2D nano sheets h-BN.

## Fix: Compatibility Needed
h-BN sheets and WPU aren’t compatible but w non covalent functionalizing boron nitride w GO makes them compatible.

## Healing Mechanism
Intrinsic-based healing

## Data
With the parameters of Schiff based waterborne polyurethane w Diimine-DiOH had self healing efficiency of 80.03% under visible light, healing time of 24h at ambient temps and tensile strength of 17.88 MPa and mechanical resistance of 20.80 MPa.

# Self-Healing in Epoxy Thermoset Polymer Films Triggered by UV Light (Moniruzzaman et al., 2016)
Types of Self-Healing Mechanisms
There are other forms of healing – capsule-based, vascular, and intrinsic.

## Polymer Focus
Focuses on cured epoxy thermoset resins modified with epoxy-functionalised photoresponsive azobenzene molecule – without resin capsules or other components not chemically joined.

## Methods Used
Study done using nanoindentation and atomic force microscopy (AFM).

## Self-Healing Mechanism
Showed good self-healing under UV irradiation only. Uses intrinsic healing mechanism triggered by UV-induced trans → cis isomerization of the azobenzene chromophore (photophore), which enables self-healing. Azobenzene is a highly abundant light-responsive molecule – changes to isomerisation of the azobenzene chromophores (reversible and repeatable isomerisation changes). UV light changes thermodynamically more stable trans-azobenzene to less stable cis form. Visible light converts cis back to trans.

## Possible Space Applications
Photoisomerization of azobenzene under UV light caused the polymer matrix to undergo bulk diffusion even below its Tb or Tm, which is favorable for space applications due to low ambient temperatures.

## Research Gap
Self-healing has been seen in azobenzene-based gels and soft polymers, but no reports exist on azobenzene-based rigid and toughened resins.

## High Survivability of Micrometeorites on Mars: Sites With Enhanced Availability of Limiting Nutrients (Tomkins et al., 2019)
type of impacts
Mars has lower energy collisions but more frequent onc es with higher particle survival due to its thin atmosphere and lower gravity.

## data frequency
~2.5×10⁻¹⁶ to 5×10⁻¹⁶ g/cm²/s flux = ~7.9 × 10⁻⁴ to 1.6 × 10⁻³ g/m²/day = ~0.29–0.59 g/m²/year

# Mars UV Spectrum Overview (Patel et al., 2002)
UV Range
The ultraviolet (UV) spectrum on Mars ranges from approximately 190 nm to 410 nm.

## Impact of Dust on UV Transmission
High dust loading in the Martian atmosphere inversely affects the ratio of direct to diffuse UV transmission. Despite this, high illumination levels persist even during intense dust storms with high optical depths.

## UV Flux Values
UV flux at the Mars surface is predominantly found in two regions:

Near 300–400 nm (UV-A and UV-B ranges)
Far 200–300 nm (short-wave UV region)
This distribution is shaped by absorption and scattering effects in the atmosphere.
Biological Significance of UV-C (However Less Common)
Short-wave UV-C radiation (200–280 nm) is extremely damaging to biological organisms and is a critical factor when considering extraterrestrial life sustainability, however, it is less common on the surface.

## Frequency of UV-A/B
UV-A and UV-B wavelengths are more reliably available on the Martian surface compared to the shorter wavelength UV-C.

## Effect of Dust on Light-Triggering
Although dust attenuates direct UV radiation, sufficient diffuse UV remains to potentially activate light-triggered materials on Mars.

# A ground‐to‐exosphere Martian general circulation model: 1. Seasonal, diurnal, and solar cycle variation of thermospheric temperatures (González-Galindo et al., 2009)

## Thermal cycles on Mars
Thin atmosphere so low heat capacity, less heat stored meaning day = 20°C, night = -73°C (large swing), surface heats quickly during the day then during night this heat radiates into space very efficiently, leads to rapid cooling.

# Biodegradable Thermoplastic Elastomers Incorporating POSS: Synthesis, Microstructure, and Mechanical Properties (McMullin, Rebar, & Mather, 2016)

## Increasing POSS content on stiffness
Increasing POSS content increases stiffness, rising from 2MPa to 13MPa with a 30% content of POSS at 13MPa - improves mechanical integrity.

## Strain to Failure data
High strain to failure of more than 1200% showing high flexibility - supports self-healing function.

## Elastic Recovery
Elastic recovery percentage shows material is able to return to original shape after deformation.

## Mechanical Stability Across Temperature Fluctuations
Increasing POSS increases mechanical stability across temp fluctuations - needed for Mars temp fluctuations.

## Prestraining importance
Prestraining (stretch before use) improves elastic recovery by up to 90% by inducing strain crystallization.

## Crystallinity benefit
Crystallinity could enhance mechanical stability and healing efficiency at low temps useful for Martian environment.

# Modeling self-healing materials (Balazs et al., 2007)

## Common simulation methods

- **Molecular dynamics**  
  - pro: captures nanoscale interactions and entropic forces accurately  
  - cons: computationally expensive for large-scale or long-time simulations

- **Lattice spring model**  
  - pros: efficient for stress analysis at crack tips, bridging nanoscale inputs to macroscale mechanical behaviour  
  - cons: may abstract away some molecular-level detail

- **Generalized lattice spring model**  
  - pros: captures mechanochemical coupling and oscillations  
  - cons: extension to 3D simulations is challenging in terms of computational efficiency

## How healing is modelled

- Molecular dynamics simulates polymer-induced entropic forces which push nanoparticles into nanoscale notches to "fill" defects  
- Lattice spring model then models how filling reduces stress concentration and crack propagation  
- Generalized lattice spring model models oscillatory chemical reaction triggered mechanically leading to chemical wave propagation  
- Chemical waves POTENTIALLY trigger local polymerization or reversible cross-linking

## Typical inputs

- polymer chain properties - length, flexibility, interaction potentials  
- nanoparticle size, concentration, interaction potentials  
- initial defect geometry  
- external conditions - mechanical compression, temperature, reagent concentration  
- reaction kinetics parameters for chemical oscillations and polymerization/cross-linking

## Typical outputs

- particle distribution  
- stress and strain fields around defects  
- spatial and temporal concentration of oxidized catalyst  
- oscillation patterns and chemical wave propagation  
- structural changes and resulting mechanical property changes

## 2D vs 3D simulations

- Generalized lattice spring model is 2D  
- a 3D extension is conceptually straightforward but computationally challenging
 

