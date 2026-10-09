# Dual-Band Microstrip Patch Antenna

**CST-based design and full-wave simulation of a dual-band microstrip patch antenna near 10 GHz and 21 GHz.**

This project explores dual-band microwave antenna design with emphasis on resonance placement, impedance matching and electromagnetic field behavior. The antenna was modeled in **CST Studio Suite** and evaluated using S-parameters, VSWR, radiation characteristics and surface-current distributions.

## Design Summary

- Dual-band response centered near **10 GHz** and **21 GHz**.
- FR4-based microstrip implementation with slot-assisted dual-band behavior.
- Full-wave EM simulation in **CST Studio Suite**.
- Evaluation of return loss, VSWR, radiation behavior and surface-current distribution.

## Selected Simulation Results

- **S11:** −36.93 dB at 10.42 GHz and −33.83 dB at 21.01 GHz.
- **VSWR:** 1.097 at 10.46 GHz and 1.082 at 21.07 GHz.
- **Radiation efficiency:** −1.784 dB near 10 GHz and −1.686 dB near 21 GHz.

These values are simulation results from the project files in this repository.

## Repository Contents

- [`Patch Antenna Design.cst`](Patch%20Antenna%20Design.cst) — CST project file.
- [`Final project report.pdf`](Final%20project%20report.pdf) — written project report.
- [`Antenna Project Presentation PDF.pdf`](Antenna%20Project%20Presentation%20PDF.pdf) — project presentation.

## Reproducing the Simulation

1. Open `Patch Antenna Design.cst` in CST Studio Suite.
2. Inspect the antenna geometry, material definitions and port setup.
3. Run the S-parameter analysis for the frequency-domain response.
4. Evaluate far-field/radiation behavior and surface-current distributions at the resonant frequencies.

## Technical Focus

`CST Studio Suite` · `EM Simulation` · `S-Parameters` · `VSWR` · `Microstrip Antennas` · `RF/Microwave Design`

## Academic Context

This project forms part of my RF/microwave engineering background and complements later work in integrated-circuit design, physical realization and design automation.
