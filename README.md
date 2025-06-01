# Automatic Classification of Thermal Phases During Steel Oxidation via PCA and Infrared Thermography Time Series

Gerardo Marx Chávez-Campos [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3945--9903-green)](https://orcid.org/0000-0003-3945-9903);  
Héctor Javier Vergara-Hernández [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--6224--1027-green)](https://orcid.org/0000-0001-6224-1027);  
Jorge Sergio Téllez-Martínez [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0587--0059-green)](https://orcid.org/0000-0003-0587-0059);  
Edgar Guevara [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--2313--2810-green)](https://orcid.org/0000-0002-2313-2810); 
Antony Morales-Cervantes [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3669--2638-green)](https://orcid.org/0000-0003-3669-2638) *(corresponding author)*

---

## Contents

- **Raw Thermograms** (`/Raw_Thermograms_CSV/`):  
  Time-series thermal data (in CSV) from six controlled high-temperature oxidation experiments on AISI 1045 steel.

- **PCA Results** (`/PCA_Results_XLSX/`):  
  Principal Component Analysis (PCA) outputs (first two components) derived from the flattened thermograms, used as input features for machine learning classification.

A total of 4019 thermographic records were compiled, covering heating, isothermal, and cooling phases.

---

## Methodology

Steel specimens (AISI 1045) were oxidized using a Joule-heating system, with thermal data captured using an Optris PI 1M infrared camera.  
PCA was applied to the flattened thermal matrices to reduce dimensionality.  
Five machine learning models (Random Forest, MLP, SVM, KNN, XGBoost) were trained and validated (5- and 10-fold CV) for automatic classification of thermal phases.

---

## Purpose

This dataset supports the development of non-invasive phase recognition tools in metallurgical processes using infrared thermography and machine learning, enhancing process monitoring and decision-making.

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Thermal_Phase_Classification_Dataset.git
2. Explore the Data:

  Raw thermograms are organized in /Raw_Thermograms_CSV/.
  PCA results for classification are in /PCA_Results_XLSX/.

3. Note: The scripts used for analysis are available upon request or will be made public after article acceptance.

## Data Availability Statement
The dataset will be permanently archived with a DOI via Zenodo upon publication.

##  Citation
If you use this dataset, please cite:

Chávez-Campos, G. M., Vergara-Hernández, H. J., Téllez-Martínez, J. S., Guevara, E., Morales-Cervantes, A. (2025). Automatic Classification of Thermal Phases During Steel Oxidation via PCA and Infrared Thermography Time Series.

##  Authors' Contributions
Antony Morales-Cervantes led the data collection. All authors contributed to data analysis and interpretation. All authors approved the final version of the manuscript for publication.

##  License
This dataset is distributed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
