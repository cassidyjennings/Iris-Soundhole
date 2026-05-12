# Iris-Soundhole

A mechanical iris aperture mechanism designed to fit into an acoustic guitar soundhole, built to investigate how variable aperture size affects the guitar's acoustic output. This project was completed as a final project for 21M.369 at MIT.

## Overview
The iris mechanism is inspired by camera lens apertures and operates on the same overlapping-blade principle. By varying the size of the soundhole opening, the mechanism changes the Helmholtz resonance properties of the guitar body, affecting volume, tone, and resonance frequency.

## Repository Structure
├── iris_v5/                  # Current iris design files (DXF, SVG, FreeCAD)
├── old_iris_designs/         # Previous iterations (v1–v4)
│   ├── iris_v1/
│   ├── iris_v2/
│   ├── iris_v3/
│   └── iris_v4/
├── data_analysis/
│   ├── measurements/         # Raw .mat measurement files
│   ├── plots/                # Generated plots by aperture size
│   └── results.ipynb         # Analysis notebook
└── guitar_assembly_photos/   # Photos of the physical assembly
