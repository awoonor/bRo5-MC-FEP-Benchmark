# bRo5-MC-FEP-Benchmark

> Structural datasets for the large-scale retrospective affinity prediction of macrocyclic ligands across five diverse targets (KRAS, PCSK9, MCL-1, JAK2, Cyclin A/B).

## De-risking Affinity Optimization for Macrocycles: FEP+ Benchmark Dataset
This repository contains the structural inputs associated with our retrospective validation of Free Energy Perturbation (FEP+) on beyond-Rule-of-5 (bRo5) macrocycles and cyclic peptides.

### Overview
Rational design of macrocycles is complicated by restricted conformational entropy, closed-loop topologies, and kinetic trapping. This dataset comprises a set of 240 macrocyclic ligands spanning five diverse therapeutic targets:

* **KRAS**
* **PCSK9**
* **MCL-1**
* **JAK2**
* **Cyclin A/B**

### Repository Contents
* `inputs/target_name`: Contains the protein receptor structures (`.pdb`) and the aligned, 3D-generated macrocyclic ligands (`.sdf`).
* `data_summary.csv`: The master file containing all experimental affinities, FEP+ predicted affinities, and calculated errors.

### Computational Details
Calculations were performed using the Schrödinger Suite (Release 2025-4). Advanced sampling protocols, including Replica Exchange with Solute Tempering (REST) and Grand Canonical Monte Carlo (GCMC) for hydration site analysis, were employed to overcome the high-energy kinetic barriers inherent to macrocyclic topologies.

### Citation
If you utilize this dataset for benchmarking your own force fields or free energy methodologies, please cite:
> Awoonor-Williams et al. "De-risking Affinity Optimization for Macrocycles and Cyclic Peptides: High Precision Free Energy Simulations across Five Diverse Targets", *Submitted*, 2026.

### License
This dataset is provided under the MIT License.
