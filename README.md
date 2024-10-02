# Comprehensive Characterization of LAT1 Cholesterol Binding Sites

I recently published this [paper](https://pubs.acs.org/doi/10.1021/acs.jctc.3c01391) in the Journal of Chemical Theory and Computation and wanted to share the Jupyter notebooks that helped generate the figures. Hopefully, this will be helpful for others who want to do similar analyses.

## Overview
The research explores cholesterol’s role in regulating the activity of the human L-type amino acid transporter 1 (LAT1; SLC7A5). LAT1 plays a key role in amino acid homeostasis in various tissues such as the blood-brain barrier, placenta, and testis. This study focuses on understanding cholesterol's impact on LAT1 structure and function by investigating four cholesterol binding sites (CHOL1-4), identified in the inward-open conformation of LAT1.

## Summary of the Study

Cholesterol has been shown to modulate membrane transporters, but its precise role in LAT1 is not fully understood. Our work employs a series of computational techniques including molecular dynamics (MD) simulations, molecular docking, and MM/GBSA free energy calculations, to explore cholesterol's interactions with LAT1.

Key findings:
- **CHOL3** is the most stable binding site, showing favorable interactions with LAT1.
- **Principal Component Analysis (PCA)** and **Center of Mass (COM) distance** analyses reveal that CHOL3 stabilizes the inward-open conformation of LAT1.
- An alternative cholesterol binding site to CHOL1 is proposed, expanding the understanding of LAT1-cholesterol interactions.

These insights lay the groundwork for future rational design of allosteric ligands targeting LAT1.

## Jupyter Notebooks

The Jupyter notebooks in this repository provide detailed guide of these analyses:
1. RMSD and RMSF analyses of Molecular Dynamics (MD) simulation trajectories
2. Principal Component Analysis (PCA) of a trajectory
3. Protein-Ligand Interaction profile of LAT1 and Cholesterol
4. Time-series plot that tracks the distances between the centers of mass (COM) of the hash and bundle domains.

## Data Availability

For access to the MD trajectory files and input files used in the study, please refer to the datasets shared on **Zenodo**:  
[Link to Zenodo Dataset](https://zenodo.org/records/10871106)

## License
The code is intended to reproduce the analyses discussed in the publication. Users can explore and modify the code for their own purposes, provided it adheres to the licensing terms below.

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](./LICENSE) file for details.

## Citation

If you use this repository or its contents in your work, please cite:

Hutchinson, K., & Schlessinger, A. (Year). Comprehensive Characterization of LAT1 Cholesterol Binding Sites. *Journal of Chemical Theory and Computation*. [https://pubs.acs.org/doi/10.1021/acs.jctc.3c01391].
