# II Materials

Computational work from Part II Materials Science at the University of Cambridge — practicals, an alloy design project, and independent simulation work. Full commit history from the original repository is preserved, so the development process behind each piece is visible in the log, not just the final result.

## Contents

| Folder | What it is |
|---|---|
| **Alloy_Design/** | Two pieces of work for the alloy design project: composition screening/ranking notebooks for hyper-duplex and martensitic style stainless steels, and a from-scratch **Allen-Cahn phase-field simulation** modelling how Cr₂O₃ oxide inclusions round off in a molten Fe-Cr-Ni-Mo alloy — connected to a fracture-mechanics argument about why that rounding matters for the alloy's toughness. This is the most substantial piece of independent work in the repo; it has its own detailed [README](./Alloy_Design/cr2o3_inclusion_sim/README.md). |
| **MD_New/** | A LAMMPS molecular dynamics study of ionic diffusion in CaF₂: building the crystal structure, running the simulation, and fitting the mean-squared-displacement output to an Arrhenius relation to extract an activation energy. |
| **P1_Composites/** | Analysis of axial and transverse tensile tests on a composite material, used to back out the two elastic moduli (E1, E2). |
| **P2_Plasticity/** | Analysis of indentation and tensile plasticity data on aluminium, brass and steel — comparing the two testing techniques and fitting a Voce hardening law to the stress-strain response. |
| **P3_Polymer_Crystallisation/** | DSC (differential scanning calorimetry) analysis of PEO50 polymer crystallisation: isolating the crystallisation and melting peaks, an Avrami analysis of crystallisation kinetics, and a growth-rate analysis linking microscope and DSC measurements of the same transitions. |
| **RPi_Project/** | A Tkinter GUI for a Raspberry Pi-controlled, displacement-driven materials test rig — live force/extension plotting, CSV logging, and control loop for a stepper-driven test — built with simulated sensors first and designed to drop in real HX711 load cell and thermocouple drivers. |
| **Supervisions/** | Notebooks written for supervision (small-group teaching) exercises and exploratory data analysis. |

## Requirements

Python 3, with the standard scientific stack: `numpy`, `pandas`, `matplotlib`, `scipy`.

```bash
pip install numpy pandas matplotlib scipy
```

Individual projects may need extras — see `Alloy_Design/cr2o3_inclusion_sim/requirements.txt` and `Alloy_Design/env_deps.yml` for the phase-field simulation's specific dependencies.
