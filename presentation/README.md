# TIPE — Energy Conversion in a Resonant Cavity

**From Wind to Electricity** · Denis O. ·  2024–2025

---

## Files

| File | Description |
|---|---|
| `tipe_resonant-cavity-en.tex` | LaTeX source (Beamer, 16:9) |
| `tipe_resonant-cavity-en.pdf` | Compiled slide deck (20 pages + appendices) |

---

## Presentation Outline

1. **Context & Motivation**
   Energy transition challenges, wind instruments as a source of inspiration,
   role of Helmholtz resonators in acoustic and energy systems.

2. **Research Question & Objectives**
   Is there an alternative method to harness the mechanical energy of wind?
   Objectives: modelling, coupling characterisation, voltage measurement, real-world tests.

3. **Theoretical Model**
   Derivation of the Helmholtz resonant frequency
   $f_0 = \frac{c}{2\pi}\sqrt{\frac{S}{VL}}$,
   coupled oscillator system (vibrating blade + cavity),
   calculation of the coupling coefficient $k$ (~1.1–1.25: very strong coupling).

4. **Experimental Setup**
   33 cl and 50 cl aluminium cans used as Helmholtz resonators.
   Three protocols: frequency sweep, free oscillation, coupled resonance.
   Signal processing in Python (discrete low-pass filter, FFT).

5. **Experimental Results**
   Measured vs. theoretical frequencies (deviation < 4%).
   Quality factor: Q ≈ 20 (sweep) up to Q ≈ 100 (free oscillation).
   Power extracted via piezoelectric quartz: **P = 3 µW / can**.

6. **Real-World Conditions**
   Tests under natural wind, hypothesis validation (constant flow,
   model linearity), study of the effect of water on f₀.

7. **Conclusion & Perspectives**
   IoT application via LoRa (one transmission every ~55 min per can,
   50 km range). Temperature and humidity sensors directly reachable.
   Future directions: PVDF materials, resonator networks (metasurfaces).

---

## Appendices

- **A** — Full derivation of f₀ (Newton's law + pressure–density)
- **B** — Coupling coefficient summary table
- **C** — Bibliographic references

---

## Compilation

Requires a standard **TeX Live** installation with the following packages:
`beamer`, `pgfplots`, `tikz`, `booktabs`, `amsmath`.

```bash
pdflatex tipe_resonant-cavity-en.tex
pdflatex tipe_resonant-cavity-en.tex   # second pass for the TOC
```

---

## Keywords

`Helmholtz resonance` · `Coupled resonance` · `Piezoelectricity` ·
`Energy conversion` · `Vibration` · `IoT` · `LoRa`

---

## Thematic Positioning (STEP 2)

- PHYSICS (Mechanics)
- PHYSICS (Physics of Matter)
- COMPUTER SCIENCE (Applied Computing)
