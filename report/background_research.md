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

# Mars Greenhouse Material Notes (Clawson, 2007)

## 1. PAR (Photosynthetically Active Radiation) on Mars
- **Mean PAR at the equator:**
  - Year 1 (MY 24-25): 25.4 ± 1.4 mol m⁻² sol⁻¹
  - Year 2 (MY 25-26): 23.3 ± 4.3 mol m⁻² sol⁻¹
- Dust storms reduce PAR by ~20% of the year; 80% remains near normal levels.
- One-quarter of light is diffuse for half of the time; diffuse light is rarely <15%.
- Multispectral radiative transfer modeling improves accuracy for photosynthetic photon flux by accounting for zenith angle and dust variations.
- Previous PAR estimates were lower:
  - Gertner, 2000: 20.8 mol m⁻² sol⁻¹
  - Ono & Cuello, 2000: 19.4 mol m⁻² sol⁻¹

## 2. UV Environment and Acceleration in Lab Tests
- Mars UV is more intense in **UVB (280–315 nm)** and **UVC (200–280 nm)** than on Earth.
- In lab simulations:
  - Total UV flux accelerated by 2.0–3.5×
  - UVB by 2.5–4.5×
  - UVC by 4.5–7.0×
  - Integrated total UV acceleration factor: ~7.52×
- Simulated Mars UV tests are shorter in duration but higher in intensity due to impracticality of full-length exposure.

## 3. Candidate Materials and UV Degradation
- **Conventional polymer composites:**
  - Nylon-based composite film and polyester-based composite fabric/film
  - High transmittance for similar load, but degrade rapidly under Mars UV
- **LARC™-CP1 (space-rated polyimide):**
  - Minimal degradation under simulated Mars UV
  - Cuts harmful UV wavelengths (including 254 nm peaks affecting polyamide degradation)
  - Protects PET-based and polyester materials
  - Long-term stability under stress in composites requires further study

## 4. Mechanical Loading and Stress-Accelerated Photodegradation
- UV-resistant polymers degrade faster under combined UV and mechanical stress than either factor alone.
- **Mechanisms:**
  - Stress reduces activation energy for polymer chain rupture → higher probability of chain scission
  - Photo- and mechano-radicals induce microcracking → propagates under stress
  - Accelerated creep and reduced creep rupture lifetime
- Observed in multiple polymers: polypropylene, polyethylene, polystyrene, Kapron (polyamide)
- Space-tested materials (e.g., Teflon® FEP on Hubble) showed embrittlement and through-thickness cracks under combined UV and stress

## 5. Creep and Creep Rupture
- **Creep stages:**
  1. Primary: slowing strain rate after initial load
  2. Secondary: quasi steady-state strain rate
  3. Tertiary: accelerated strain → necking → rupture
- **UV irradiation effects:**
  - Increase chain scission → shift load to remaining chains → faster creep
  - Cause crosslinking → embrittlement → brittle fracture
- **Models used:** Maxwell, Voigt, Kelvin, generalized Voigt-Kelvin (Andre & Pinto, 2004)
- Photodegradation affects activation energies and cross-linking, influencing creep rates
- **Arutyunyan model** predicts time to creep rupture for viscoelastic polymers under UV:
  - Includes initial stress, polymer viscosity, lateral strain coefficient, UV intensity effect

## 6. Experimental Methods
- **Multi-sample tensile creep testing apparatus:**
  - Radial sample placement to minimize UV intensity variation
  - Loads controlled independently via stepper motors
  - Strain measured via clamp displacement
  - Chamber purged with nitrogen to eliminate humidity/O₂ effects
- **Sample preparation:**
  - LARC™-CP1 spun-cast to 7 µm, cut with precision jig
  - Widths: 4.32 mm, 6.35 mm; length: 29 mm
- **UV irradiation:**
  - 1000 W xenon-arc lamp simulating Mars UV
  - Lamp spectra measured across radial positions; variation ±10–20%
- **Temperature control:**
  - Irradiated samples: 33 ± 4 °C
  - Unirradiated samples matched short-term creep rates at 37 °C

## 7. Results on LARC™-CP1
- Creep rupture life decreases under UV; accelerated UV testing shows susceptibility
- Some samples show brittle fracture with little tertiary creep → embrittlement likely due to crosslinking
- Residual stresses: exposed side more damaged, sample curling observed
- Mechanical loading + UV irradiation reduces lifespan more than UV or stress alone (Vershinina et al., 1964)
- Temperature increase of ~20 °C slightly affects creep rupture but not enough to meet Mars mission lifespan requirements

## 8. Design Implications for Greenhouses
- Separate removable protective layer recommended (LARC™-CP1 laminated to FEP)
- Thin to maintain PAR transmittance (0.80–0.86)
- Can be replaced periodically to mitigate UV and dust degradation
- Diffuse PAR favors greenhouse design over solar collectors
- Optimal structural composite materials and life estimation require creep rupture data
- Consideration for dust and abrasion protection: FEP can help protect LARC™-CP1 without significantly reducing PAR

## 9. Conclusions
- LARC™-CP1 is highly UV-resistant but still vulnerable to stress-accelerated degradation
- Mars UV environment, particularly UVC/UVB, is a moderate threat to polymers over long durations
- PAR availability is sufficient for greenhouse operations; dust storms can reduce availability 20% of the year
- Accurate extrapolation of lab accelerated testing to Mars is speculative, but the data support further 

# Notes on: Outgassing Effect in Polymeric Composites Exposed to Space Environment (Pastore et al., 2020) 

## 1. Effects of CO₂ atmosphere on polymer chain stability and oxidation
- Focus is only on **hard vacuum** (10⁻⁵ mbar and below) + thermal cycling.
- FT-IR shows chemical modifications in polymer chains due to outgassing.
- **No CO₂ chemistry or oxidation studied.**

## 2. Data on swelling, cracking, or outgassing under low pressures (~6 mbar)
- Outgassing tested at **10⁻⁵ mbar** (more extreme than 6 mbar Martian CO₂).
- Key findings:
  - Outgassing = release of residual monomers, additives, adsorbed gases.
  - Leads to **structural depletion** and possible **micro-defects/cracking**.
  - Outgassing strongly enhanced above **100 °C**.
- No explicit **swelling data**, but depletion implies swelling/cracking risk under cycling.

## 3. Relevance to sealing/coating layers in habitats
- Outgassing compromises **long-term stability of sealing polymers**, increasing permeability.
- Contamination risk: condensed volatiles may affect **solar panels, optics, habitat windows, coatings**.
- Results by material type:
  - **CF-epoxy**: stable, within limits → good candidate.
  - **GF-epoxy**: borderline → acceptable with **thermal pre-conditioning**.
  - **KF-epoxy**: excessive volatile loss → **not acceptable**.
- Implies **thermal bake-out pre-treatment** may be required for sealing/coating layers.

# Mars Suit Material Notes – Environmental Considerations (Marcy et al., 2004)

## Effects of CO₂ Atmosphere
- EVOH (ethylene-vinyl alcohol copolymer) selected for the pressure/bladder layer due to excellent gas barrier properties.
- PET/EVOH co-extrusion used in insulation layers to reduce CO₂ permeation.
- PTFE and silicone elastomers chosen for chemical stability and resistance to oxidation in harsh environments.

## Low-Pressure Behavior (~6–7 mbar)
- PVDC coatings applied to nylon layers to prevent moisture absorption and protect against vacuum effects.
- Nylon scrim layers in insulation allow relative slip, accommodating thermal expansion and contraction.
- Multi-layer laminates (e.g., PET, aluminized polyester) provide structural and barrier support under low-pressure conditions.

## Relevance to Sealing/Coating Layers
- EVOH, PET/EVOH, PTFE, and PVDC layers serve as effective barriers to gases, moisture, UV, and chemicals.
- Barrier layers are compatible with adjacent materials and contribute to overall structural and environmental protection.
- Multi-layer approach (barrier + structural + dampening layers) ensures cumulative protection and could inform ha

# PE-LLD Degradation Under Multiple Stressors (Corti et al., 2010)

## Simultaneous Stressors & Synergy
- Agricultural **PE-LLD mulch films** with pro-oxidants tested under:
  - Sunlight → fungal incubation → thermal aging (45 °C).
- **COi increase:**
  - Test (pre-oxidized) films: `0.0096 COi/day`
  - Controls: `0.0068 COi/day`
  - → ~20% higher oxidation rate in pre-oxidized vs. pristine films.
- **Respirometry:**  
  - Pre-oxidized films showed **much higher CO₂ production** than controls.  
  - Both had equal glucose → fungi were metabolizing **oxidation products** as an extra carbon source.

## Evidence of Biotic + Abiotic Synergy
- **FT-IR:** Stronger peaks for `C=O`, `C=C`, `OH` groups **only** in pre-oxidized + fungal films → fungi enhanced breakdown of oxidation products.
- **TGA:** Pre-oxidized + fungal films showed:
  - Lower thermal stability.
  - Onset degradation temp drop + ~2% early weight loss.
- **DSC:** Higher crystallinity in pre-oxidized + fungal films → fungi consumed low-molecular-weight oxidized fractions, leaving more ordered crystalline residues.
- **GC–MS (literature comparison):**
  - Many small molecules (carboxylic acids, short-chain organics) formed during abiotic oxidation **disappeared** after biotic treatment.
  - Confirms microbes actively metabolized degradation products.

## Performance Differences vs. Single-Stressor Tests
- **Sunlight only:** Generates oxidation products (hydroperoxides, ketones, aldehydes, carboxyls).
- **Fungi only:** No significant degradation of pristine PE.
- **Thermal only (low T):** Slow oxidation, insufficient for biodegradation.
- **Combination (UV + thermal + fungal):**
  - Faster COi growth (~20%).
  - Higher CO₂ evolution.
  - Lower TON in TGA.
  - Stronger chemical/structural changes in FT-IR + DSC.
  - → Clear evidence of **synergistic acceleration**.

## Acceleration Factors / Quantitative Notes
- `~20%` faster oxidation rate (COi/day) in oxidized vs. control films.
- **CO₂ evolution:** Higher in oxidized + fungal samples (not quantified, but “remarkably elevated”).
- **Thermal onset degradation temp:** Decreased (exact °C drop not given here; sunlight-only data showed ~`119 °C` reduction).
- **Concentration-dependent biodegradation:**
  - Low polymer concentration (0.006%): `54–64%` degradation.
  - High concentration (0.05%): `28–34%` degradation.

# Mars-Relevant Light-Responsive Polyurethane Systems (Li et al., 2017; Zhang et al., 2017; Aguirresarobe et al., 2016)

## Absorption Maxima & Spectral Windows
| System | Light Wavelength (nm) | Other Stimuli | Observed Response |
|--------|----------------------|---------------|-----------------|
| Azobenzene (AZO) | 365 | Heat 50-80°C, pH acidic | Trans-cis isomerization, color change, swelling control |
| Spiropyran (SP) | 365 | Visible/dark, force | Ring opening to MC, stretch color change |
| Coumarin-PU | 365, <300 | pH (micelles) | [2+2] cycloaddition, photocleavage, crosslinking, drug release |
| Anthracene-PU | >300, <300 | Heat >120°C | [4+4] cycloaddition, reversible crosslinking, self-healing |
| o-Nitrobenzyl (o-NB) PU | 320-480 | None | Irreversible photocleavage, amine release, rapid drug release (~20s) |
| Rhodamine B (RhB) PU | 365 | Heat 60-80°C | Reversible photochromism, shape memory |

## Light-Induced Reactions
- **Photocleavage**
- o-NB: irreversible, releases functional groups, fast drug release
- Dithiocarbamate (LBCL): reversible, initiates secondary radical polymerization → self-healing + crosslinking
- **Photodimerization / Reversible Crosslinking**
- Coumarin: [2+2] cycloaddition (UV 365 nm), photocleavage (<300 nm)
- Anthracene: [4+4] cycloaddition (UV >300 nm), reversible with heat (>120°C)

## Applications
- Drug delivery: Coumarin- and o-NB-based PU micelles for targeted release
- Shape memory and self-healing: RhB-PU, Anthracene-PU, SP-PU
- Sensors: AZO-PU for pH and light changes
- Coatings: UV-curable PU acrylates, PU/MWCNT composites for mechanical reinforcement and photoresponsive properties

# Self-Healing Polymer Bilayer Films (PBFs) (Kim et al., 2020)

## Materials and Composition
- **Bottom layer:** Colorless polyimide (CPI)
- **Top layer:** Polydimethylsiloxane (PDMS) embedded with linseed oil microcapsules (LOMC)
- **Optimal LOMC content:** 5 wt% for effective self-healing

## Mechanism of Self-Healing
- Healing occurs when cracks rupture LOMC, releasing linseed oil (LO)
- LO reacts with environmental factors (air, moisture, temperature, UV) to fill cracks and polymerize
- UV-light triggers photochemical-induced drying, rapidly solidifying LO and completing healing

## Multi-Stimuli Response
- **Air:** Slow healing under ambient conditions
- **Moisture (70% RH):** Gradual healing observed
- **Heat (70°C):** Partial healing within 20 min
- **UV-Light (1.2 kW Hg lamp, 30 cm):** Complete healing within 20 min

## Healing Performance
- **UV-light irradiation (20 min, 5 wt% LOMC)**
  - Fracture stress recovery: ~91%
  - Fracture strain recovery: ~85%
  - Toughness recovery: ~71%
- Strong interfacial adhesion between CPI and PDMS maintained during tensile tests
- Viscoelastic properties (storage modulus E′, tan δ) remain nearly identical after healing

## Optical and Barrier Properties
- PBFs remain highly transparent and colorless
- Water vapor permeability after UV-light healing: 35.4 g/m²/day
- Effective in blocking ingress of oxygen and water molecules

## Fabrication Notes
- LOMC prepared via poly(urea-formaldehyde) in-situ polymerization
- Particle size controlled by agitation speed (optimal: 1500 rpm → 108 μm average diameter)
- CPI synthesized via two-step imidization (BAPS + 6FDA)
- PBF assembled using layer-by-layer spin coating of PDMS + LOMC onto CPI

## Characterization Techniques
- SEM, OM, and 3D micro-CT imaging for morphology and healing observation
- FTIR for chemical monitoring of LO release and polymerization
- TGA for thermal stability
- DMA for viscoelastic properties
- Tensile testing for mechanical recovery
- UV-Vis and colorimetry for optical properties
- Contact angle and surface energy for adhesion and wettability

## Key Takeaways
- PBF 5 wt% exhibits rapid, mono-component, multi-stimuli self-healing
- UV-light is particularly effective for fast photochemical healing
- System is catalyst-free, transparent, mechanically robust, and commercially promising for flexible electronics

# Photopolymerization Kinetics (Luu et al., 2020)

## System Studied
- Photopolymerization of multifunctional monomers
- BAPO photoinitiator under UV irradiation (λ = 355 nm)
- Sample thickness: 250 µm
- Temperature: 25 °C
- Photoinitiator concentration: 0.0256 M

## Light Intensity Conditions
- Range: 0.01 – 3 mW/cm²
- Measured:
  - Conversion yield (CY)
  - Rate of polymerization (Rp)
  - Macroradical concentration

## Dose–Response Relationships
- Rp and CY increase with light intensity
- Higher UV dose → faster polymerization → higher conversion in given time
- Low intensities (0.01–0.1 mW/cm²) → significant reduction in polymerization rate
- Macroradical concentration and formation rates ∝ light intensity

## Threshold Values
- Very low light intensities show delayed initiation and slow propagation
- Indicates a minimum intensity threshold required for effective polymerization
- Dark polymerization after UV exposure allows reaction to continue at low dose

## Kinetic Modeling Insights
- Polymerization divided into four regimes:
  1. Normal polymerization (no diffusion limitation)
  2. Autoacceleration (termination partially diffusion-controlled)
  3. Reaction-diffusion (kp and kt affected by diffusion)
  4. Autodeceleration (propagation diffusion-limited, termination still reaction-diffusion controlled)
- Rate constants kp and kt depend on UV intensity
- Reaction-diffusion proportionality constants (rdRpA, f_cp, f_ct) estimated from conversion data
- Quantitative dependence on UV dose confirmed

## Key Takeaways
- Clear dose–response relationship: faster polymerization and higher conversion at higher light intensity
- Threshold behavior apparent at low-intensity conditions
- Provides quantitative rate constants and radical concentrations
- Data could be extrapolated to weaker UV sources (e.g., solar or Mars-equivalent)

# Self-Healing Microvascular Fiber-Composites (Patrick et al., 2014)

## Overview
This study demonstrates **multiple cycles of in situ delamination healing** in structural fiber-reinforced composites using **microvascular delivery of reactive fluids**. Three-dimensional vascular networks are embedded in the composite, allowing repeated healing with **no degradation of inherent fracture properties**.

## Key Findings

### 1. Maximum Number of Healing Cycles
- Tested up to **three consecutive healing cycles** in the herringbone (interpenetrating) vascular network.
- **Healing efficiency exceeded 100%** in some cases due to enhanced polymerization at the fracture surface.
- Parallel (isolated) vascular networks showed lower recovery, especially in later cycles.

### 2. Degradation Behavior
- Healing efficiency is **threshold-dependent and localized**, not strictly linear or exponential.
  - Well-mixed regions (herringbone network) fully recover or exceed virgin fracture toughness.
  - Poorly mixed regions (parallel network) show incomplete polymerization and reduced efficiency.
- **Raman spectroscopy** revealed stoichiometry-dependent polymerization:
  - Near-target R:H ratio (2:1) → full recovery.
  - Under-stoichiometric (≈1.5:1) → partial recovery.
- Indicates **local chemical availability controls degradation/recovery**, consistent with a threshold-based mechanism.

### 3. Crosslink Density / Bond Exhaustion
- **Confocal Raman and fluorescent imaging** measured the chemical state of healed fracture interfaces.
  - Regions with multiple cycles show polymerization of epoxy (oxirane consumption), confirming bond formation.
  - Regions near the terminal crack front had partially polymerized material, indicating **progressive bond exhaustion** in areas of limited mixing.
- No absolute crosslink density values reported, but chemical mapping provides **direct evidence of bond availability limits across cycles**.

## Mechanistic Insights
- Herringbone vasculature promotes interpenetrating fluid interfaces → improved in situ mixing → higher mechanical recovery.
- Fiber bridging in composites adds an additional energy absorption mechanism during repeated cycles.
- Vascular architecture is critical: poor mixing reduces efficiency and shows localized chemical limitations

# Inflatable Habitat Materials and Testing (Valle et al., 2019)

| Layer / Component       | Materials Used                                           | Mechanical Properties / Notes                                                                                  | Failure Modes / Testing Insights                                                                 | Candidate for Self-Healing |
|-------------------------|---------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|----------------------------|
| **Liner (inner)**       | Nomex, Kevlar felt                                      | Flame and puncture resistant, easy-to-clean, acoustic dampening                                              | No specific failure modes; protects bladder from crew damage                                      | Low – protective only      |
| **Bladder (gas barrier)** | Combitherm, urethane-coated Nylon, Cepac® HD-200       | Flexible, durable, low permeability across temperature range, oversized for redundancy                        | Can leak if punctured; critical for pressure containment                                         | **High – pressure-critical** |
| **Restraint Layer (structural)** | Kevlar, Vectran webbing (tight basket weave or sewn hoop) | Carries hoop and axial loads, flexible and foldable, factor of safety 4                                      | Axial straps fail first in creep-burst tests; non-uniform load and stitching affect TTF         | **High – structural-critical** |
| **MMOD Layer**           | Nextel, open-cell polyurethane foam, Kevlar rear wall | Multi-material layup for hypervelocity impact protection, vacuum-packed for launch                             | Three failure modes in hypervelocity testing: damage to restraint only, both restraint and bladder, none | Medium – repair minor damage possible |
| **Thermal Protection (TPS)** | Multi-layer insulation (MLI), Mylar + Kapton      | Passive temperature regulation                                                                                 | No specific failure modes mentioned                                                             | Low – passive insulation    |
| **Atomic Oxygen (AO) Protection** | Betaglass                                       | Protects materials from LEO atomic oxygen degradation                                                        | AO exposure can discolor Kevlar, minimal structural effect                                       | Medium – outer layer repair potential |

# Key Mechanical / Testing Notes
- **Module-Level Creep-Burst Testing:**  
  - 1/3 scale TransHab module, 6,000 lb/in axial straps, 12,500 lb/in hoop straps  
  - Test pressure: 145 psig (74% of burst), axial straps failed in 49 min, hoop straps intact  
  - Module-level creep life is reduced vs. strap-level; stitching/weaving affects performance  

- **Folding / Deployment:**  
  - Inner liner, bladder, restraint layer folded around core; outer layers (MMOD, MLI, AO) folded as gore patterns  
  - Each layer individually attached to folded bladder/restraint layer for controlled deployment  

# Candidate Integration for Self-Healing (Lee et al., 2015)
- **Bladder Layer:** Primary pressure containment; self-healing could prevent leaks  
- **Restraint Layer:** Axial straps fail first; self-healing could extend structural life  
- **MMOD Layer:** Outer layer; self-healing could repair minor hypervelocity damage  

# Self-Healing Polymer Coatings & Composites – Key Findings

## 1. Interface Adhesion Between Coatings and Fabrics/Composites
- Self-healing PRC (PAN-resin-cure) nanofibers embedded in PDMS matrices restore adhesion after mechanical damage.
- Polymerized PDMS acts as a “glue” adhering broken fibers to each other and the surrounding matrix.
- Co-electrospun core-shell fibers maintain mechanical integrity and provide reinforcing interfacial layers.

## 2. Delamination / Loss of Healing After Repeated Cycles
- **Mechanical cycling tests** (tensile tests repeated up to four times) show:
  - PAN (non-self-healing) mats: Young’s modulus drops ~90% after four cycles; catastrophic failure occurs.
  - PRC mats: Young’s modulus drops ~30% after four cycles; stress-strain curves largely preserved.
- PDMS composites with PRC fibers maintain or increase Young’s modulus (up to 1.4× after fourth cycle).
- Self-healing occurs via resin monomer and cure released from broken fiber cores, polymerizing within micro-cracks.
- Recovery requires ~24 h rest at room temperature for polymerization and property restoration.

## 3. Case Studies / Aerospace-Relevant Applications
- PRC nanofiber mats and composites simulate micro-crack accumulation in aerospace composites under periodic loading.
- Healing mechanism restores stiffness and prevents catastrophic delamination during moderate strain (~15%).
- Tensile tests up to catastrophic failure (~30% strain) show self-healing is limited when fiber sections separate too far.
- 24 h recovery periods align with practical requirements for daily or periodic healing in aerospace structural materials.
- Compatible PDMS matrix ensures reinforcement and adhesive restoration at ply surfaces.

## 4. Material & Fabrication Notes
- Core-shell nanofibers:
  - Core A: resin monomer (dimethyl siloxane)
  - Core B: cure (dimethyl-methyl hydrogen-siloxane)
  - Shell: PAN (polyacrylonitrile)
- Co-electrospinning produces mutually entangled nanofiber mats, embedded in PDMS to form composites.
- Fiber diameters:
  - PAN mat: 588 ± 135 nm
  - PRC mat: resin fibers 1.32 ± 0.50 μm, cure fibers 373 ± 105 nm
- Tensile testing regimes:
  - I: Elastic
  - II: Plastic
  - III: Catastrophic failure
