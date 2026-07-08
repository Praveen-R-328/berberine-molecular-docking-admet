# Molecular Docking and ADMET Prediction of Berberine Against Type 2 Diabetes Mellitus Targets

<p align="center">
<img src="Workflow/workflow.jpeg" width="1000">
</p>

## Project Overview

This project explores the therapeutic potential of berberine against Type 2 Diabetes Mellitus (T2DM) through an integrated computational drug discovery workflow. The study combines network pharmacology, molecular docking, protein–ligand interaction analysis, and ADMET prediction to identify potential molecular targets and evaluate the drug-likeness of berberine as a prospective therapeutic candidate.

---

## Project Highlights

- Integrated network pharmacology and molecular docking workflow
- Blind docking using CB-Dock2 followed by targeted docking using AutoDock Vina
- Best docking affinity: **−10.3 kcal/mol**
- Comprehensive ADMET and toxicity evaluation
- Protein–ligand interaction analysis using Discovery Studio and PyMOL

---
  
## Objectives

* Predict molecular targets of berberine
* Identify T2DM-associated therapeutic targets
* Construct protein–protein interaction networks
* Perform molecular docking against PPARG
* Analyze protein–ligand interactions
* Evaluate pharmacokinetic and toxicity profiles
* Assess the drug discovery potential of berberine using computational methods

---

## Computational Workflow

The overall computational workflow employed in this study is illustrated in the figure above.

---

## Methodology

The computational workflow employed in this project consisted of the following steps:

1. Literature survey to understand the role of berberine in Type 2 Diabetes Mellitus (T2DM).
2. Retrieval of the berberine chemical structure from **PubChem**.
3. Ligand preparation using **Open Babel** for geometry optimization and **AutoDockTools (MGLTools)** for PDBQT conversion.
4. Prediction of potential therapeutic targets using **SwissTargetPrediction**.
5. Collection of T2DM-associated genes from **GeneCards**.
6. Identification of common therapeutic targets through **Venn analysis**.
7. Construction and analysis of the protein–protein interaction (PPI) network using **STRING**.
8. Network visualization and exploration using **Cytoscape**.
9. KEGG pathway enrichment analysis to identify the key therapeutic target (**PPARG**).
10. Retrieval of the PPARG crystal structure (PDB ID: **2P4Y**) from the **RCSB Protein Data Bank**.
11. Protein preparation using **PyMOL**, including removal of water molecules and co-crystallized ligands.
12. Docking preparation using **AutoDockTools (MGLTools)** by adding polar hydrogens, assigning Kollman charges, and generating PDBQT files.
13. Molecular docking using **AutoDock Vina**.
14. Blind docking and binding pocket prediction using **CB-Dock2**.
15. Selection of the optimal docking pose based on binding affinity and interaction profile.
16. Protein–ligand interaction analysis using **BIOVIA Discovery Studio Visualizer**.
17. Three-dimensional visualization of the docked complex using **PyMOL**.
18. Prediction of drug-likeness, physicochemical, pharmacokinetic, and ADMET properties using **SwissADME**.
19. Toxicity prediction, including LD₅₀ estimation, using **ProTox-3**.
20. Integrated interpretation of docking, interaction, ADMET, and toxicity results to evaluate the therapeutic potential of berberine against T2DM.

---

## Repository Structure

```text
berberine-molecular-docking-admet
│
├── README.md
├── Workflow/
├── Protein/
├── Ligand/
├── Docking/
├── ADME/
├── Toxicity/
├── References/
└── Molecular_Docking_and_ADMET_Prediction_of_Berberine.pdf
```

---

## Software and Databases

|            Tool / Database         |                            Purpose                             |
|------------------------------------|----------------------------------------------------------------|
| Scientific Literature              | Literature survey and background research                      |
| PubChem                            | Retrieval of berberine chemical structure                      |
| Open Babel                         | Ligand preparation and geometry optimization                   |
| AutoDockTools (MGLTools)           | Preparation of ligand and protein PDBQT files                  |
| SwissTargetPrediction              | Prediction of potential therapeutic targets                    |
| GeneCards                          | Collection of T2DM-associated genes                            |
| Venn Analysis                      | Identification of common therapeutic targets                   |
| STRING                             | Protein–protein interaction network construction               |
| Cytoscape                          | Network visualization and analysis                             |
| KEGG                               | Pathway enrichment analysis                                    |
| RCSB Protein Data Bank (PDB)       | Retrieval of PPARG crystal structure                           |
| PyMOL                              | Protein preparation and 3D structural visualization            |
| AutoDock Vina                      | Molecular docking                                              |
| CB-Dock2                           | Blind docking and binding pocket prediction                    |
| BIOVIA Discovery Studio Visualizer | Protein–ligand interaction analysis                            |
| SwissADME                          | Drug-likeness, pharmacokinetic profiling, and ADMET prediction |
| ProTox-3                           | Toxicity prediction                                            |

---

## Key Results
The docking study demonstrated favorable binding of berberine toward PPARG. The best-ranked docking pose exhibited a binding affinity of **−10.3 kcal/mol**, supporting the potential interaction of berberine with the selected therapeutic target.

### Molecular Docking

| Parameter                           | Result               |
| ----------------------------------- | -------------------- |
| Target Protein                      | PPARG (PDB ID: 2P4Y) |
| Ligand                              | Berberine            |
| CB-Dock2 Best Score                 | **−9.5 kcal/mol**    |
| AutoDock Vina Best Binding Affinity | **−10.3 kcal/mol**   |
| Selected Docking Pose               | Mode 1               |

---

## ADMET Evaluation

SwissADME analysis suggested favorable drug-likeness and acceptable pharmacokinetic properties of berberine. The compound was evaluated for physicochemical characteristics, oral bioavailability, medicinal chemistry filters, and Lipinski's Rule of Five to assess its suitability as a potential drug candidate.

---

## Toxicity Prediction

ProTox-3 predicted an oral LD₅₀ of **200 mg/kg**, corresponding to **Toxicity Class III**, indicating moderate acute toxicity. These findings provide preliminary insights into the safety profile of berberine for further investigation.

---

## Project Report

The complete project report can be accessed here:

📄 **Molecular_Docking_and_ADMET_Prediction_of_Berberine.pdf**

---

## Future Scope

* Molecular Dynamics Simulation (GROMACS)
* MM/PBSA Binding Energy Analysis
* QSAR Modeling
* Virtual Screening of Natural Products
* AI-Assisted Drug Discovery
* Structure-based virtual screening

---

## Skills Demonstrated

- Medicinal Chemistry
- Computational Chemistry
- Computer-Aided Drug Design (CADD)
- Molecular Docking
- Network Pharmacology
- Protein–Ligand Interaction Analysis
- ADMET Prediction
- Toxicity Prediction
- Cheminformatics
- Scientific Data Analysis

---

## Major Findings

|          Finding         |   Observation  |
|--------------------------|----------------|
| Best AutoDock Vina Score | −10.3 kcal/mol |
| Best CB-Dock2 Score      | −9.5 kcal/mol  |
| Target Protein           | PPARG          |
| Toxicity Class           | III            |
| Predicted LD50           | 200 mg/kg      |

---

## Author

**Praveen R**

BS-MS Student

Indian Institute of Science Education and Research (IISER) Tirupati

Research Interests

- Medicinal Chemistry
- Drug Discovery
- Computational Chemistry
- Molecular Docking
- Computer-Aided Drug Design (CADD)
- AI-assisted Drug Discovery
- Pharmaceutical Research

---

## References

Scientific references used in this project are available in the **References** folder.

---

## Acknowledgements

This project was completed as an independent academic study to develop practical skills in computational medicinal chemistry, molecular docking, network pharmacology, and ADMET prediction.

The author gratefully acknowledges the developers and maintainers of the open-access databases, software, and web servers that made this work possible, including:

- PubChem
- Open Babel
- AutoDockTools (MGLTools)
- SwissTargetPrediction
- GeneCards
- STRING
- Cytoscape
- KEGG
- RCSB Protein Data Bank (PDB)
- AutoDock Vina
- CB-Dock2
- BIOVIA Discovery Studio Visualizer
- PyMOL
- SwissADME
- ProTox-3

The author also acknowledges the AI in Drug Discovery Training and Internship conducted by **Ethical EduFabrica Pvt. Ltd.** in association with **Pravega, IISc Bangalore**, which provided valuable practical exposure to computational drug discovery methodologies.

---

## Citation

If you find this repository useful for academic or educational purposes, please cite the original software, databases, and publications listed in the References folder.
