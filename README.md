# SolPredio
### 📘 Overview

This project presents a machine learning pipeline to predict the aqueous solubility of organic molecules using molecular descriptors derived from SMILES strings. It employs the classic Delaney solubility dataset, which is commonly used in cheminformatics as a benchmark for regression tasks in molecular property prediction.

The approach uses:

- RDKit for computing molecular descriptors
- Pandas for data preprocessing
- Scikit-learn for linear regression modeling and evaluation
- The goal is to demonstrate how even a simple model, when powered by chemically meaningful features, can yield strong predictions in drug discovery or material science domains.

### 🚀 How to Run

1. Clone the repository and install dependencies:

`pip install rdkit-pypi pandas scikit-learn matplotlib seaborn`

2. Open the notebook:

`jupyter notebook predict_solubility.ipynb`

### 📚 References
- Delaney, J.S. (2004). ESOL: Estimating Aqueous Solubility Directly from Molecular Structure. J. Chem. Inf. Comput. Sci. 44(3): 1000–1005.
- RDKit: Open-source cheminformatics. https://www.rdkit.org
