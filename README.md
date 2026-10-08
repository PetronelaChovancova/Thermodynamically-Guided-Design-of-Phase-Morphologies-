# Thermodynamically Guided Design of Phase Morphologies in Recycled Polypropylene via Reactive Compatibilisation with EPDM-g-MA: Role of Polarity and Chemical Reactivity

## Overview

This repository contains the experimental data supporting the article published in the **Journal of Polymer Research**.

The study investigates how the **polarity** and **chemical reactivity** of a dispersed phase control phase morphology and mechanical performance in **recycled polypropylene (rPP)** blends compatibilised with **EPDM-g-MA**. Two dispersed phases are compared:

- **Polystyrene (PS)**: low polarity and non-reactive towards maleic anhydride
- **Polyamide 5,6 (PA56)**: polar and reactive towards maleic anhydride

Surface free energies obtained from contact angle measurements are used to predict interfacial interactions thermodynamically. These predictions are then compared with the tensile properties of the blends.

---

# Repository Structure

```
.
├── README.md
├── SFE.xlsx
├── Tensile_results_overview.csv
├── PS_strain_at_break_results.csv
└── PA56_strain_at_break_results.csv
```

---

# Materials Analysed

| Material | Description |
|-----------|-------------|
| PP | Virgin polypropylene |
| rPP | Recycled polypropylene |
| EPDM | Ethylene–propylene–diene rubber |
| EPDM-g-MA | Maleic anhydride grafted EPDM (compatibiliser) |
| PS | Polystyrene (non-polar, non-reactive dispersed phase) |
| PA56 | Polyamide 5,6 (polar, reactive dispersed phase) |

---

# Data Files

## SFE.xlsx

Surface free energy of each material, with one sheet per material.

Contains:

- Contact angles of water and diiodomethane
- Total surface free energy
- Dispersive component
- Polar component

All values were calculated using the **Owens–Wendt–Rabel–Kaelble (OWRK)** model.

---

## Tensile_results_overview.csv

Tensile results for all formulations (Batch 1–16, PS blends and PA56 blends).

Contains, for each specimen:

- Young's modulus (MPa)
- Tensile stress at yield (zero slope) (MPa)

together with the mean and standard deviation for each formulation.

---

## PS_strain_at_break_results.csv

## PA56_strain_at_break_results.csv

Results for each specimen of the PS and PA56 blends.

Contains:

- Maximum stress (MPa)
- Strain at break (%)
- Sample code

Five specimens were tested per formulation (four valid results for PA56-B2).

---

# Citation

If this notebook contributes to your research, please cite the accompanying scientific publication.

---

# License

This repository is provided to promote **transparent**, **reproducible**, and **open scientific research**. If you use these data in your own research, please cite the original publication.
