## (Clawson, 2007)
LARC™-CP1 (colourless polyimide developed by NASA): 
- degredation accelerated by stress
- high UV-resistance
- high UV and stress causes embrittlement
. mechanism - stress lowers the chain rupture activation energy -> UV forms radicals which leads to chain scission (longer chain split into shorter chains) = faster creep (slow, permanent deformation) mainly tertiary (accelerated strain)

State variables (what is happening internally e.g. chain scission - chains split)
chain scission
effective activation energy (current activation energy - so here the stress lowers the activation energy so the current activation energy (effective) is the internal factor that has changed, e.g. activation is lower right now whereas rupture is the final value needed)
creep (permanent deformation, it is deformed, it is a set change)

relevant equations for tracking state variables in the simulation
chain scission:
dt / dϕ​ = −kUV​ϕ
ϕ = fraction of polymer chains still intact 1 = all intact, 0 = all broken, 0.75 = 75% intact
kUV​ = rate constant for UV-induced chain scission
d (extremely small changes of ...)

effective activation energy:
k = Aexp(−(Eeff​​ / RT))
Eeff = effective activation energy (calculated via 𝐸eff = E0 - ΔEstress, E0 = baseline rupture energy, ΔEstress = energy reduction due to stress)
k = chain scission or creep rate
Aexp = how often chains attempt to rupture (chains are always vibrating so always have the chance to overcome the activation energy)

creep:
dϵter / dt ​​= kcreep​ ⋅ f(CS,Eeff​,σ)
ϵ = stress (the internal stress actually experienced by the material)
d (extremely small changes of ...) = infinitesimal changes
𝜎 = applied stress (stress applied to the material)
η = viscosity (how fast the liquid flows, high would be slow flow)
𝐸 = elastic modulus (how stiff the material is, how much it resists being deformed)
CS = number of chains breaking (chain scission)
Eeff = effective activation energy
f is just stating it is a function

**[note]** creep acceleration needs to be coded based on stress + UV levels

PE-LLD (linear, low density polyethylene):
- degradation accelerated by UV, thermal, and fungal exposure
. mechanism - oxidation degredation -> chain scission -> embrittlement (less ductile - less able to bend, will fracture more likely)

# Mechanical Stress / Creep
## (Yuan et al., 2021)
- Creep stages: primary, secondary, tertiary
- UV + mechanical stress reduces activation energy → chain scission
- Models: Maxwell, Voigt, Kelvin, generalized Voigt-Kelvin, Arutyunyan model

# Thermal Effects
## (Tavanaei et al., 2022; Yang et al., 2006; Montarnal et al., 2011; Cash et al., 2015; Wojtecki et al., 2016)
- Thermal cycling: rapid heating/cooling on Mars
- Thermal aging: PE-LLD, POSS elastomers
- Intrinsic/self-healing polymers: Vitrimers, epoxy/PCL blends affected

# Chemical / Oxidative Effects
## (Pernigoni et al., 2021)
- Perchlorate oxidation: reduces modulus & fracture toughness 
- Synergistic effects: UV + oxidation + thermal stress
- Extrinsic healing systems vulnerable; intrinsic systems more robust

# Multi-Stressor / Synergistic Effects
## (Tavanaei et al., 2022)
- PE-LLD: sunlight + fungi + thermal → 20% faster oxidation, higher CO₂ evolution
- Cumulative stress accelerates creep, chain scission, embrittlement
- Relevant for Martian polymer longevity
