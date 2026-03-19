# Environmental Chemicals CYP-Mediated DDI Models

This repository provides PBPK (physiologically based pharmacokinetic) models developed in PK-Sim/MoBi for environmental chemicals and CYP-mediated drug–drug interaction (DDI) assessment.

## Overview

This repository includes:
- PBPK models of **DEHP (di(2-ethylhexyl) phthalate)** and its primary metabolite **MEHP (mono(2-ethylhexyl) phthalate)**
- Mechanistic evaluation of **CYP2C9-mediated inhibition by MEHP**
- Simulation files for **victim drugs primarily metabolized by CYP2C9**

The models are intended to support both:
- Mechanistic static model (MSM)-based DDI assessment
- PBPK-based DDI simulation using intracellular unbound inhibitor concentrations

---

## Victim Drug Models (CYP2C9 substrates)

The repository includes PBPK model files for the following CYP2C9 substrate drugs:

- **Diclofenac**
- **Mefenamic acid**
- **Tolbutamide**
- **S-warfarin**

These models are used as victim drugs to evaluate CYP2C9-mediated DDI potential.

---

## Model Sources

The victim drug models were obtained or adapted from the following sources:

- **Diclofenac**  
  Open Systems Pharmacology example repository  
  https://github.com/Open-Systems-Pharmacology/Example_Diclofenac  

- **Mefenamic acid**  
  Open Systems Pharmacology repository  
  https://github.com/Open-Systems-Pharmacology/Mefenamic-acid-Model  

- **S-warfarin**  
  Kuo Geng et al., 2024  

- **Tolbutamide**  
  Everett J. Perkins et al., 2018  
  (SimCYP model translated into PK-Sim/MoBi format)

---

## Notes

- Some models were adapted or reformatted for compatibility with PK-Sim/MoBi.
- Parameter adjustments may have been performed for integration into DDI simulations.
- Users should refer to original sources for model validation and detailed assumptions.

---

## Purpose

This repository aims to:
- Provide reproducible PBPK workflows for environmental chemical risk assessment
- Enable quantitative evaluation of CYP-mediated DDI potential
- Bridge environmental exposure modeling with pharmacokinetic interaction analysis

---

## Acknowledgement
<sub>
This study was supported by the Korea Environmental Industry & Technology Institute (KEITI) through the Core Technology Development Project for Environmental Diseases Prevention and Management (RS-2021-KE001333), funded by the Ministry of Environment (MOE), Republic of Korea.
</sub>
