# Trained Spectral Neighbor Analysis Potential (SNAP)

This repository contains the trained Spectral Neighbor Analysis Potential (SNAP)

### 1. SNAP for Ti₃SiC₂ MAX Phase
#### Paper: *"Unveiling Kink Band Formation Mechanism in MAX Phases"*

The following files are included in this repository:
- **TSC_commat.snapcoeff** – SNAP coefficient file
- **TSC_commat.snapparam** – SNAP parameter file

#### Usage Instructions
To apply SNAP in LAMMPS simulations, include the following commands in input script:

pair_style snap
\
pair_coeff * * TSC_commat.snapparam TSC_commat.snapcoeff Ti Si C

#### Citation
If use this potential, please cite the following paper:  
Hossain, R., Ogata, S. Unveiling kink band formation mechanism in MAX phases. Commun Mater 6, 51 (2025). https://doi.org/10.1038/s43246-025-00766-7


