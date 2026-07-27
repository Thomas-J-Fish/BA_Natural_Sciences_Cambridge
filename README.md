# BA Natural Sciences, University of Cambridge

Code and data analysis from my undergraduate degree in the Natural Sciences Tripos at the University of Cambridge, specialising in **Materials Science**.

The Tripos is structured in stages: a broad-based first year (Part IA) across several sciences, a second year (Part IB) where students narrow to three subjects, and a final year (Part II) of full specialisation. This repository consolidates the coding-heavy work from the second and third years:

- **Part II — Materials Science** (final year): the bulk of the repository, spanning practicals, an alloy design project, and independent simulation work.
- **Part IB — Quantitative Environmental Science (QES)**: a multidisciplinary second-year course combining physics, maths, biology and chemistry to study climate and environmental systems — building numerical climate models, analysing environmental datasets, and writing a policy paper aimed at a non-technical audience.

Across both, code was used for three main things: processing and analysing experimental data (mechanical testing, calorimetry, glaciological records), building physical simulations from first principles (phase-field, molecular dynamics, coupled ODE climate models), and building small pieces of lab infrastructure (a GUI for a Raspberry Pi-controlled test rig).

This repo brings together three previously separate repositories now that the degree is complete, each kept as a subfolder.

## Contents

| Folder | Course | What's in it |
|---|---|---|
| [`II_Materials/`](./II_Materials) | Part II Materials Science | Alloy design and a phase-field simulation of oxide inclusion behaviour, mechanical testing analysis (composites, plasticity), polymer crystallisation kinetics, a molecular dynamics diffusion study, and a Raspberry Pi test-rig GUI. Full commit history preserved — see the [subfolder README](./II_Materials/README.md). |
| [`Glacier_Analysis/`](./Glacier_Analysis) | Part IB QES | Data analysis of long-term glacier retreat in Austria, written up as a policy paper connecting glacial melt to ski-tourism economics. |
| [`Thermohaline_Circulation_Model/`](./Thermohaline_Circulation_Model) | Part IB QES | A 4-box ocean-atmosphere carbon cycle model, extended to test a climate feedback mechanism under a simulated CO₂ emissions pulse. |

Each subfolder has its own README with more detail on goals, methodology, and results.
