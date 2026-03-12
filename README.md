# Energy conversion in a resonant cavity — From wind to electricity

**TIPE — Travaux d'Initiative Personnelle Encadrés**  
Author: O. Denis  
Year: 2024–2025

---

## Abstract

This project investigates the amplification of mechanical vibrations in a Helmholtz resonator coupled to a vibrating blade, with the goal of converting wind energy into electricity via a piezoelectric material (quartz). The approach combines theoretical modelling, numerical simulation and experimental validation.

**Research question:** How can the conversion of mechanical energy into electrical energy be optimised through coupled resonance in a Helmholtz cavity, under the assumption of constant airflow?

---

## Thematic positioning

- Physics — Mechanics
- Physics — Physics of Matter
- Computer Science — Applied Computing

**Keywords:** coupled resonance · Helmholtz resonator · piezoelectricity · vibration · energy conversion

---

## Repository structure
```
tipe-resonant-cavity/
├── docs/                  # MCOT sheets (FR + EN), annotated bibliography
├── experiments/           # Experimental protocols, measurements, raw results
├── presentation/          # Defence slide deck (.pptx), simulation, data
└── README.md
```

---

## Key physical principles

### Helmholtz resonator
Resonant frequency:

$$f = \frac{v}{2\pi} \sqrt{\frac{A}{LV}}$$

- $v$ : speed of sound (~343 m/s)
- $A$ : neck cross-sectional area
- $L$ : neck length
- $V$ : cavity volume

### Coupled resonance
Interaction between a vibrating blade and the cavity to maximise the amplitude of mechanical displacements. Synchronisation of the natural frequencies of both systems is critical.

### Piezoelectricity
Mechanical stress → electrical polarisation (direct effect, used here as a generator). Efficiency depends on the material, its placement within the device, and losses due to mechanical dissipation.

---

## Timeline (DOT)

| Period | Stage |
|---|---|
| Sep. 2024 | Introduction to energy harvesting methods, in particular piezoelectric conversion |
| Sep.–Oct. 2024 | Research on coupled resonance and Helmholtz resonators |
| Nov. 2024 | Theoretical design of the experimental protocol — aluminium cans chosen as resonators |
| Dec. 2024 | Theoretical calculation of resonant frequencies, equipment preparation |
| Jan. 2025 | First experimental tests — conclusive results |
| Jan.–Feb. 2025 | Coupling tests — inconclusive experiments |
| Mar. 2025 | Vibrating blade + Helmholtz cavity system — convincing results |
| May–Jun. 2025 | Hypothesis verification, functional tests under real-world conditions |

---

## References

1. Boyer A., Leblanc C., Molinier A., Sauvage L. — *Helmholtz Resonators: Acoustic Resonances and Cavity Optimisation* — Physics Olympiad, École Alsacienne (2011)
2. Hoang T. — *Piezoelectric Energy Harvesting Device: Modelling, Fabrication and Characterisation* — PhD thesis, University of Tours, GREMAN (2019)
3. Zhang Q. — *Renewable Micro-Energy Harvesting through Multiphysics Material Coupling* — PhD thesis, University of Grenoble, LOCIE (2011)
4. Sabat R. — *Acoustic Metasurface through Coupling between Helmholtz Resonators for Low-Frequency Sound Attenuation* — PhD thesis, University of Lorraine (2017)
5. Ahmed-Seddik B. — *Broadband Vibratory Energy Harvesting Systems* — PhD thesis, University of Rennes 1 (2020)
6. Bruneau M. — *Acoustics of Cavities: Models and Applications* — CNRS Research Report (2018)
7. Damy G., Gauthier M. — *Energy Production from Ocean Swells* — CNEXO-COB (1981)
