# HALLIE
Australian HANK model
# Introduction 
These codes are for HALLIE (Heterogeneous Agent Lens Linking Inequality and Equilibrium) model.

Copyright © RBA, 2026. All rights reserved.
This repository contains research code associated with a forthcoming paper. No license is currently granted for reuse, modification, or redistribution. Licensing information will be updated following publication of the associated research.

# Getting Started: How to run the model
The codes are written in Python using sequence-space jacobian solution method developed in Adrien Auclert, Bence Bardóczy, Matthew Rognlie, Ludwig Straub (2021). Those codes have been run on CML, but should also work in any other Python environment.

To run the model firstly store steady state and jacobian dictionaries by running "calibration_HALLIE_baseline.ipynb" notebook. Skip this step if the dictionaries are already stored. Run the notebook "IRFs_with_stored_results.ipynb" to compute the model and plot IRFs.

# Organisational structure of the codes
1. The folder "Model_code" contains the code for model equations.
2. The folder "sequence_jacobian" contains sequence space jacobian toolbox codes.
3. The folder "saved models" contains saved models (not pushed to git) - better not to store on github as they are of large sizes.

A ton of learning materials to get acquainted with the solution methodology can be found here: https://github.com/shade-econ/sequence-jacobian

If anything is unclear, feel free to reach out to Ekaterina Shabalina, Tommy Iao, or Marco D'Amico.
