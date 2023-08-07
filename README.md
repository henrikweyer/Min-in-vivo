# Min-in-vivo
This repository contains supplementary simulation code for the project

**Robust and resource-optimal dynamic pattern formation of Min proteins _in vivo_**
by Ziyuan Ren*, Henrik Weyer*, Laeschkir Würthner, Dongyang Li, Cindy Sou, Daniel Villarreal, Erwin Frey, and Suckjoon Jun.

The code is associated with the following figures:
_Concentration phase diagrams_ Fig. 4
_Pattern wavelength and oscillation period_ Fig. 4
_Time-averaged concentration profile_ Fig. 3
_SI/S12-LSA-robustnessSweep_ Fig. S12
_SI/S13-pfOnset-classification_ Fig. S13
_SI/S15_16_17-patternTypes-parameterSweeps_ Figs. S15, S16, S17

## Comsol simulations
Large-scale simulations are performed in the finite-element software Comsol. Exemplary setup files are provided that contain the settings to perform the simulations in Comsol 6.0/6.1.

The simulation results are exported in txt files which are converted to hdf5 files and analyzed in the provided Mathematica notebooks.

## Mathematica notebooks
The Mathematica notebooks only reference to Comsol2Mathematica2hdf5.nb which is assumed to be in the same folder as the notebook. Mathematica is used to analyze the Comsol simulations but also to perform independent simulations in a reduced 1+1D geometry and a linear stability analysis.

