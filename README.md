# Potentials parameter file examples

This repository hosts example scripts for interacting with and generating LAMMPS-compatible interatomic potential parameter files, either from other formats or from published equations and parameter tables.

## Code requirements

The scripts contained in this repository are based on the standard scientific Python packages (numpy, pandas, etc) and the packages that are part of the NIST Interatomic Potentials Repository project.  For the IPR packages, the two that are predominately used here are
- potentials, which includes tools for building and analyzing EAM parameter files.
- iprPy, which collects a number of property evaluation checks that can be performed on the generated parameter files.  Specifically, examples here use the iprPy QuickChecks to rapidly evaluate a large number of properties.