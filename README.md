# 🧬 SARS-CoV-2 Mpro Drug Discovery Project

This repository presents a full Computer-Aided Drug Design (CADD) workflow for identifying potential inhibitors of the **Main Protease (Mpro)** of SARS-CoV-2. The study combines molecular docking, QSAR modeling, and ADME/Tox screening of candidate ligands such as Aspirin, Curcumin, and related compounds.

---

## 📌 Project Objectives

- Prepare ligands using SMILES and generate 3D conformers.
- Perform molecular docking using **AutoDock Vina**.
- Build and evaluate QSAR models for pIC50 prediction.
- Screen ADME and toxicity profiles using **SwissADME** and **pkCSM**.
- Visualize protein-ligand interactions and model performance.

---

## 📁 Repository Structure

```
SARS-CoV-2-Mpro-Drug-Discovery/
├── notebooks/
│   ├── 1_ligand_preparation.ipynb
│   ├── 2_docking_pipeline.ipynb
│   ├── 3_qsar_modeling.ipynb
│   └── 4_adme_screening.ipynb
├── data/
│   ├── ligands/               # SMILES, PDBQT files
│   ├── protein/               # 6LU7.pdb
│   └── docking_results/
├── media/                     # Plots and visualizations
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🛠️ Tools & Libraries

- **RDKit** – Cheminformatics and descriptor calculation
- **Open Babel** – File conversion (.smi to .pdbqt)
- **AutoDock Vina** – Molecular docking
- **scikit-learn** – Machine learning for QSAR
- **SwissADME / pkCSM** – ADME/Tox prediction
- **PyMOL / Chimera** – Visualization

---

## 🚀 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run each notebook in order
cd notebooks
jupyter notebook
```

---

## 👤 Author

**Basem Abdelrahman**  
Bioinformatics Advanced Diploma – LLRI  
[GitHub Profile](https://github.com/basemmak)

---

## 📄 License

This project is licensed under the MIT License.
