# Trained Spectral Neighbor Analysis Potential (SNAP)

This repository contains the trained SNAP potential.

## 1. SNAP for Ti₃SiC₂ MAX Phase 
### Citation
If you use this potential in your research, please cite:  
*"Unveiling Kink Band Formation Mechanism in MAX Phases."*

The following files are included:
- **TSC_commat.snapcoeff** – SNAP coefficient file
- **TSC_commat.snapparam** – SNAP parameter file

## Usage Instructions
To apply this potential in your LAMMPS simulations, use the following command in your input script:

pair_style snap
\
pair_coeff * * TSC_commat.snapparam TSC_commat.snapcoeff Ti Si C
