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
 
# The initiating radical yields and the efficiency of polymerization for various dental photoinitiators excited by different light curing units (Neumann et al., 2006)

| Photoinitiator | Type / Absorption | Co-initiator | FP (mol/Einstein) | PAE (Optilux / LED) | Photopolymerization Efficiency ×10⁴ (Optilux / LED) | Mw (g/mol) | Likely Mars UV Performance |
|----------------|-----------------|-------------|-----------------|-------------------|--------------------------------------------------|------------|---------------------------|
| Camphorquinone (CQ) | Visible (400–500 nm, max 470) | EDB | 6.61 ×10⁻³ | 2.14 / 3.62 | 1.42 / 2.39 | 2.91 ×10⁶ | Poor, absorbs mostly visible; low UVA/UVB activation |
| Phenylpropanedione (PPD) | α-diketone, UVA + slight visible | EDB | 9.46 ×10⁻³ | 2.56 / 2.73 | 2.42 / 2.58 | 1.40 ×10⁶ | Moderate, some UVA absorption; better with broad spectrum |
| Monoacylphosphine oxide (MAPO, Lucirin TPO) | UVA | None | 31.64 ×10⁻³ | 4.38 / 0.40 | 13.86 / 1.27 | 1.76 ×10⁶ | Excellent under broad-band UV; poor under blue LED-only |
| Bisacylphosphine oxide (BAPO, Irgacure 819) | UVA | None | 9.62 ×10⁻³ | 5.15 / 1.86 | 4.96 / 1.79 | 2.34 ×10⁶ | Very good under broad-band UV; moderate under LED |

# Self‑healing materials for space applications: overview of present development and major limitations (Pernigoni et al., 2021)

## 1. Material Properties & Performance

- **Vitrimers**
  - Efficient thermal fusion of multiple layers and thermoforming.
  - Glass transition temperature ≈ 110 °C
  - Young’s modulus ≈ 2.2 GPa
  - Stress at failure ≈ 70 MPa
  - Continuous glass fiber-reinforced composites can be welded multiple times due to exchange reactions.

- **Mechanical Performance Examples**
  - 3D-printed photoelastomer composites: tensile strength ~100% recovery after 60 min at 60 °C.
  - Epoxy/PCL blends: fracture toughness increased by ~30% after thermal healing.
  - Metal alloys (SUS304, Ti): Electropulsing repair closes microcracks.

## 2. Space Environment Requirements

- **Micrometeoroids & Orbital Debris (MMOD)**
  - Small debris (<1 mm) → minor erosion
  - Larger debris (~1 cm) → potential catastrophic failure

- **Thermal Cycling**
  - Range: −120 °C to +120 °C
  - Can induce cracking, deformation, aging

- **Radiation**
  - UV, GCR, SPE can trigger polymer degradation or self-healing in specialized coatings

- **High Vacuum & Outgassing**
  - Leads to chemical modification, mass loss, contamination

- **Atomic Oxygen (ATOX) in LEO**
  - Erodes polymers; mitigated by self-healing coatings like UPy-POSS and PI-b-PDMS

- **Challenges**
  - Combined effects of vacuum, radiation, impacts, and thermal cycling are largely unexplored
  - Space-specific testing needed

## 3. Self-Healing Systems and Mechanisms

### Extrinsic Mechanisms
- Use embedded healing agents (microcapsules, metallic particles)
- Example: Al₂O₃–Ti composites heal 20 μm cracks at 800–900 °C
- UV-responsive microcapsule coatings trigger healing via mechanical damage or UV light

### Intrinsic Mechanisms
- Healing arises from reversible chemical bonds
- Examples:
  - Supramolecular polymers & ionomers with Kevlar®/Nextel® for hypervelocity impact shielding
  - Autonomous thiol-ene-trialkylborane polymers seal breaches post-MMOD impact
  - Vitrimers with reversible cross-linking for multiple repair cycles

### Metal/Alloy Repair
- Electropulsing induces atomic bonding and microcrack closure

### ATOX-Resistant Coatings
- UPy-POSS: SiO₂ passivation layer
- TSP-POSS + phosphorus polyimides: double passivation, reduced weight loss
- PI-b-PDMS: minimal mass loss, high stability

## 4. Degradation and Chemical Effects in Mars-Like Environments

| Material / System | Degradation Mechanism (Mars-Relevant) | Mechanical Effect | Healing Impact |
|------------------|---------------------------------------|-----------------|----------------|
| Polyurethane | Oxidation by perchlorates; chain scission | Reduced Young’s modulus & fracture toughness | Lower healing efficiency; potential bond failure |
| Epoxy / PCL blends | Oxidation; thermal stress | Increased brittleness; crack propagation | Reduced thermal healing efficiency |
| Vitrimers | Oxidative damage, radiation-induced chain scission | Lowered stress at failure if repeated cycles | Reduced reversibility of cross-links; slower healing |
| 3D-printed photoelastomers | UV degradation, chain scission | Tensile strength loss over time | Delayed or incomplete crack closure |
| Supramolecular polymers / Ionomers | Oxidation, radical attack | Reduced stiffness | Autonomous healing may be hindered |
| Ti / SUS304 alloys | Surface oxidation | Microcrack propagation | Electropulsing still effective but may require higher current |
| UPy-POSS / TSP-POSS coatings | Oxidation from reactive species | Minimal mass loss | Maintains healing; passivation reduces degradation |
| PI-b-PDMS | Thermal & chemical stability | Maintains mechanical integrity | Effective localized healing |

**Notes:**
- Oxidative stress from perchlorates and reactive radicals is the dominant chemical degradation mechanism on Mars.
- Thermal cycling and UV exacerbate degradation.
- Extrinsic systems are most vulnerable; intrinsic systems with protected backbones or coatings are more robust.

## 5. Key Insights & Future Directions

- **Material Selection**
  - Vitrimers, intrinsic self-healing polymers, and oxidation-resistant coatings are most promising.
  - Extrinsic healing systems require encapsulation for long-term function.

- **Environmental Simulation Needs**
  - Combine **oxidizing soil simulants, UV/radiation, and thermal cycling** for realistic durability testing.

- **Performance Trade-Offs**
  - Oxidative and chemical degradation reduce healing cycles, mechanical strength, and fracture recovery.

- **Future Directions**
  - Mars-tailored polymers with oxidation-resistant backbones and intrinsic healing
  - Protective coatings for localized damage mitigation
  - Integrated monitoring of mechanical properties and healing efficiency
