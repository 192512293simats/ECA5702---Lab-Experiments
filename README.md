# ECA5702 – Nanoelectronics and Devices (Old Lab Manual)

This repository contains simulation files, experiment records, and supporting materials for **ECA5702 – Nanoelectronics and Devices**, based on the **older laboratory manual** used for the course.

> **Manual status:** The experiments documented here follow the old lab manual. For the updated experiment list and current procedures, refer to the [ECA5702 New Lab Experiments repository](https://github.com/192512293simats/ECA5702-Lab-Experiments-NEW). Check the new manual before performing an experiment, because tool names, procedures, parameters, and experiment order may have changed.

## About the Repository

The repository preserves work completed against the old manual, including NanoHUB-based device simulations, nanoparticle optical simulations, and crystallographic analysis using FullProf. It is intended as an academic reference for reviewing the older experiment set and its simulation outputs.

## Software and Online Tools

Depending on the experiment, the old manual uses:

- **Mie-Plot / Mie theory calculator** – nanoparticle scattering, absorption, and extinction.
- **NanoHUB tools** – quantum wells, quantum dots, periodic potentials, nanowires, tunnelling, MOSFETs, FinFETs, CNTFETs, GFETs, magnetic tunnel junctions, and biosensors.
- **FullProf Suite** – Rietveld refinement and lattice-parameter determination from X-ray diffraction data.

Availability and interface details of online tools may change over time. Follow the current tool instructions and your course's updated manual.

## Experiments Covered in the Old Manual

The following list reflects the **12 experiments listed in the old manual's table of contents**. Folder names in this repository may use shortened titles.

### Experiment 1 – Simulation of Scattering and Absorption of Multi-layer Spheres and Core–Shell Nanoparticles Using Mie-Plot

Simulates the optical response of spherical nanoparticles and core–shell structures. The experiment examines extinction, absorption, and scattering spectra as particle material, core diameter, shell material, shell thickness, wavelength range, and surrounding-medium refractive index are varied.

**Main concepts:** Mie theory, optical cross-sections, core–shell nanoparticles, and localized surface plasmon resonance.

### Experiment 2 – Simulation of Density of States of Quantum-Well Structures with Various Nanometre Thicknesses

Uses a NanoHUB nanocrystalline-composite/quantum-well-related tool as described in the old manual to compare outputs for different material thicknesses and configurations.

**Main concepts:** quantum confinement, energy subbands, and density of states (DOS).

**Manual note:** The old manual's tool-selection instructions and its experiment title are not perfectly aligned. Verify the intended tool and procedure against the new manual.

### Experiment 3 – Simulation of Energy States of Quantum Dots Using NanoHUB

Models quantum-dot structures and examines their energy states for different geometries, dimensions, materials, and simple or multilayer configurations.

**Main concepts:** quantum confinement, discrete energy levels, size-dependent electronic properties, and semiconductor nanostructures.

### Experiment 4 – Kronig–Penney Model

Uses the Periodic Potential Lab to study the energy-functional-versus-energy response for periodic potentials. The old manual includes step-well, triangular-well, and sinusoidal-potential examples.

**Main concepts:** periodic potentials, allowed energy bands, forbidden bandgaps, and electron behaviour in crystal lattices.

### Experiment 5 – Band-Structure Simulation for Graphene and Carbon Nanotubes Using NanoHUB

The old manual describes nanowire band-structure simulations using the ABACUS band-structure tool, including circular nanowire geometry and comparisons between semiconductor materials such as InAs and AlGaAs.

**Main concepts:** band structure, nanowires, quantum confinement, and material-dependent electronic properties.

**Manual note:** The old experiment title mentions graphene and CNTs, while the procedure and case studies focus substantially on nanowires. Confirm the required scope using the updated manual.

### Experiment 6 – Demonstration of Quantum Tunnelling

Uses the Piece-Wise Constant Potential Barriers Sim2L tool to study transmission and reflection through potential barriers. The old manual includes transmission/reflection coefficient plots and grid comparisons.

**Main concepts:** quantum tunnelling, potential-barrier width and height, transmission probability, reflection, and resonant behaviour.

### Experiment 7 – MOSFET Scaling Analysis and Subthreshold Swing Calculation Using NanoHUB

Uses the FetToy simulator to explore single-gate MOSFET behaviour while varying gate and drain voltages and examining drain current and transconductance efficiency.

**Main concepts:** MOSFET I–V characteristics, saturation, threshold voltage, gate control, and transconductance efficiency.

### Experiment 8 – Simulation of I–V Characteristics of FinFET, CNTFET, and GFET Using NanoHUB

Covers three device types:

- **FinFET:** studies voltage–current characteristics and the effect of device geometry and gate control.
- **CNTFET:** studies carbon-nanotube transistor behaviour, including the effects of CNT diameter and length.
- **GFET:** studies graphene field-effect transistor characteristics, including the influence of gate voltage, channel dimensions, and carrier mobility.

**Main concepts:** nanoscale transistor operation, I–V characteristics, quantum/material effects, and device-geometry dependence.

### Experiment 9 – Simulation of Tunnelling Magnetoresistance (TMR) by Varying Barrier Height Using NanoHUB

Uses the Magnetic Tunnel Junction Lab to investigate the tunnelling magnetoresistance response for different barrier heights.

**Main concepts:** magnetic tunnel junctions, spin-dependent tunnelling, barrier properties, and TMR.

### Experiment 10 – Biosensor and Bio-FET Characteristics Using NanoHUB

Uses the BioSensor Lab to study BioFET threshold voltage and transfer characteristics for different electrolyte pH values. The old manual describes an EGFET configuration, DNA as the analyte, and receptor-density and temperature settings.

**Main concepts:** BioFET sensing, pH response, threshold-voltage shifts, transfer curves, and Nernstian sensitivity.

### Experiment 11 – Calculate the Potential of a pH Sensor Using NanoHUB

Uses the ENBIOS 1D tool to investigate sensor potential while changing electrolyte pH and insulator dimensions.

**Main concepts:** electrolyte–insulator–semiconductor (EIS) sensors, pH-dependent potential, and the effect of insulator thickness.

### Experiment 12 – Rietveld Refinement and Lattice-Parameter Determination (Single-Phase Material) Using FullProf

Uses FullProf to refine X-ray diffraction data and determine crystal lattice parameters. The old manual includes examples involving AlSb, CeO₂, ZnO, and Na₀.₅Bi₀.₅TiO₃.

**Main concepts:** X-ray diffraction, Rietveld refinement, lattice parameters, peak-profile functions, and fit-quality indicators such as Rp, Rwp, and χ².

## Repository Contents

The repository currently includes experiment folders and a copy of the old laboratory manual (`LAB Mannual.pdf`). The folders shown in the repository may contain simulation screenshots, experiment files, or other uploaded materials.

- **Experiment folders:** Refer to the individual folders for the materials available for each experiment.
- **`LAB Mannual.pdf`:** Reference copy of the old manual.
- **README:** Overview of the old experiment set and links to the updated repository.

Not every experiment folder necessarily contains every item (such as source files, screenshots, calculations, or results). Check each folder for its actual contents.

## Old Manual vs. New Manual

This repository is intentionally labelled as the **old-manual version**. The newer repository is the reference point for the updated experiment set:

**[Open ECA5702-Lab-Experiments-NEW on GitHub](https://github.com/192512293simats/ECA5702-Lab-Experiments-NEW)**

Use the new repository to check the latest experiment titles, tools, and procedures. Do not assume that an old-manual procedure is still valid for the new syllabus without checking.

**Course:** ECA5702 – Nanoelectronics and Devices  
**Department:** Electronics and Communication Engineering (ECE)  
**Manual basis:** Older laboratory manual  
**Updated experiment reference:** [ECA5702 New Lab Experiments](https://github.com/192512293simats/ECA5702-Lab-Experiments-NEW)
