## Martian Environmental Parameters for Simulation (Amils et al., 2007)

A baseline of important factors of Martian conditions was found from current research (see `sources.md`), out of the provided conditions, the following conditions were selected for the Martian simulation environment:

- **Low Temperature**: -35°C
- **Oxidation**: perchlorates in soil, chemical degradation.
- **Radiation Exposure**: Estimated solar UV flux, particularly UVA/UVB relevant to photoinitiators.
- **Micrometeoroid Events**: Incorporated using probabilistic models from MRO data.

### Rationale

These factors were chosen because they are the most probable environmental conditions to effect the polymer.

## Data Input for Each Factor

### Low Temperature
- **POLYMER**
  - Glass transition temperature (Tg)
  - Tensile strength, flexibility
  - Thermal contraction coefficients
- **MARS**
  - -35°C

### Radiation Exposure
- **POLYMER**
  - UV absorption spectra of the polymer
  - Rate of photodegradation by UVA/UVB
- **MARS**
  - Activation efficiency of photoinitiators under Martian UV flux

### Micrometeoroid Events
- **POLYMER**
  - Self-healing response time after micrometeoroid damage
  - Damage thresholds from high-velocity impacts
- **MARS**
  - Impact frequency and energy from Mars Reconnaissance Orbiter data

## Mars UV Spectrum Overview (Patel et al., 2002)

### UV Range
The ultraviolet (UV) spectrum on Mars ranges from approximately 190 nm to 410 nm.

### Impact of Dust on UV Transmission
High dust loading in the Martian atmosphere inversely affects the ratio of direct to diffuse UV transmission. Despite this, high illumination levels persist even during intense dust storms with high optical depths.

### UV Flux Values
UV flux at the Mars surface is predominantly found in two regions:

- Near 300–400 nm (UV-A and UV-B ranges)
- Far 200–300 nm (short-wave UV region)
This distribution is shaped by absorption and scattering effects in the atmosphere.

### Biological Significance of UV-C (However Less Common)
Short-wave UV-C radiation (200–280 nm) is extremely damaging to biological organisms and is a critical factor when considering extraterrestrial life sustainability, however, it is less common on the surface.

### Frequency of UV-A/B
UV-A and UV-B wavelengths are more reliably available on the Martian surface compared to the shorter wavelength UV-C.

### Effect of Dust on Light-Triggering
Although dust attenuates direct UV radiation, sufficient diffuse UV remains to potentially activate light-triggered materials on Mars.

## Thermal cycles on Mars (González-Galindo et al., 2009)

Thin atmosphere so low heat capacity, less heat stored meaning day = 20°C, night = -73°C (large swing), surface heats quickly during the day then during night this heat radiates into space very efficiently, leads to rapid cooling.

## High Survivability of Micrometeorites on Mars: Sites With Enhanced Availability of Limiting Nutrients (Tomkins et al., 2019)

### Type of Impacts
Mars has lower energy collisions but more frequent ones with higher particle survival due to its thin atmosphere and lower gravity.

### Data Frequency
~2.5×10⁻¹⁶ to 5×10⁻¹⁶ g/cm²/s flux = ~7.9 × 10⁻⁴ to 1.6 × 10⁻³ g/m²/day = ~0.29–0.59 g/m²/year
