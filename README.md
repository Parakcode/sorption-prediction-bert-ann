# Sorption Prediction of Veterinary Pharmaceuticals with BERT and ANN

This repository contains the code and dataset for the paper:

**"Predicting Sorption Behavior of Veterinary Pharmaceuticals via BERT and Artificial Neural Network"**

## 📂 Repository Structure
- `notebooks/` → Colab notebooks for preprocessing, training, and evaluation  
- `data/` → Dataset used in the study (`data.csv`)  
- `models/` → Trained model weights (if shared)  
- `results/` → Example outputs, figures, and evaluation metrics  

## 📊 Dataset
The dataset includes molecular descriptors, SMILES representations, and measured sorption coefficients (log Kd) for veterinary pharmaceuticals.  
- File: `data/data.csv`  
- Columns:  
  - `Compound` – compound name or ID  
  - `SMILES` – molecular structure in SMILES notation  
  - `Descriptors` – physicochemical descriptors (logP, pKa, MW, etc.)  
  - `Kd` – experimental sorption coefficient (log Kd)  

If you use this dataset, please cite both this repository and the original sources referenced in the manuscript.  

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Parakcode/sorption-prediction-bert-ann.git
