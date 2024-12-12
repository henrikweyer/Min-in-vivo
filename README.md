# Min-in-vivo
[![DOI](https://zenodo.org/badge/675778595.svg)](https://zenodo.org/badge/latestdoi/675778595)

This repository contains supplementary simulation code for the project

**Robust and resource-optimal dynamic pattern formation of Min proteins _in vivo_**

by Ziyuan Ren*, Henrik Weyer*, Michael Sandler*, Laeschkir Würthner*, Haochen Fu, Chanin B. Tangtartharakul, Dongyang Li, Cindy Sou, Daniel Villarreal, Judy E. Kim, Erwin Frey, and Suckjoon Jun.

The code is associated with the following figures:

_Concentration phase diagrams_ Fig. 3 and Fig. S14

_MinE concentration shift_ Fig. 3

_SI/LSA-robustnessSweep_ Fig. S15

_SI/pfOnset-classification_ Fig. S16

_SI/Pattern wavelength and oscillation period_ Fig. S18

_SI/patternTypes-parameterSweeps_ Figs. S20 - S25

## Comsol simulations
Large-scale simulations are performed in the finite-element software Comsol. Exemplary setup files are provided that contain the settings to perform the simulations in Comsol 6.1.

The simulation results are exported in txt files which are converted to hdf5 files and analyzed in the Mathematica notebooks provided.

## Mathematica notebooks
The Mathematica notebooks reference to Comsol2Mathematica2hdf5.nb which is assumed to be in the same folder as the referencing notebook.
Mathematica is used to analyze the Comsol simulations, and it is used to perform simulations in the reduced 1+1D geometry and the linear stability analysis.

