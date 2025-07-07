# AMEData_Prep

This repository provides preprocessing tools for preparing and analyzing nuclear mass data from the Atomic Mass Evaluation (AME) datasets, including **AME2016** and **AME2020**. The scripts and notebooks are tailored for machine learning workflows and scientific studies in nuclear physics.

---

## 📁 Repository Structure

- `data_Prep.ipynb`:  
  Jupyter Notebook for:
  - Parsing `mass16.txt` (AME2016) and `mass_1.txt` (AME2020)
  - Extracting nuclear properties: proton number (Z), neutron number (N), mass number (A), and mass excess
  - Identifying updated or new nuclei in AME2020
  - Saving the processed data as `test.data`

- `data/` *(to be created)*:  
  Directory for storing raw AME dataset files.

---

## ✅ Features

- Clean preprocessing pipeline for AME datasets
- Highlights new or modified nuclei in AME2020 vs AME2016
- Exports clean `.data` files suitable for ML tasks
- Supports physical feature construction for modeling (Z, N, A, etc.)

---

## 🚀 Getting Started

Follow these steps to set up and run the data preparation pipeline:

### 1. Clone the Repository

```bash
git clone https://github.com/aysbt/AMEData_Prep.git
cd AMEData_Prep

## Run the Notebook
Open the notebook in Jupyter or Jupyter Lab:

```bash
jupyter notebook data_Prep.ipynb



 


