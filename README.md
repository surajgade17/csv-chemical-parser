# CSV Chemical Parser 🧪

A Python tool for reading, validating and cleaning
chemical datasets using RDKit and Pandas.

## Project Information
- **Phase:** 1 - Python Foundation
- **Author:** Suraj Gade
- **GitHub:** github.com/surajgade17
- **Goal:** Cheminformatics & AI Drug Discovery

## What This Project Does
Reads a chemical dataset containing SMILES strings,
validates each molecule using RDKit, extracts molecular
properties and saves cleaned data to a CSV file.

## Project Flow
1. Create chemical dataset with Pandas
2. Validate SMILES strings using RDKit
3. Extract molecular properties (MW, Formula, LogP)
4. Separate valid and invalid molecules
5. Save cleaned data to CSV file
6. Print summary statistics

## Features
- Validate SMILES strings using RDKit
- Extract molecular formula and weight
- Calculate LogP values
- Separate valid and invalid molecules
- Save cleaned dataset to CSV
- Print summary statistics

## Tools Used
- Python 3
- Pandas
- RDKit
- Google Colab

## Dataset
| Name | SMILES | Solubility |
|------|--------|------------|
| Ethanol | CCO | -0.24 |
| Aspirin | CC(=O)Oc1ccccc1C(=O)O | -1.10 |
| Benzene | c1ccccc1 | -1.85 |
| Caffeine | CN1C=NC2=C1C(=O)N(C(=O)N2C)C | -0.07 |
| Ibuprofen | CC(C)Cc1ccc(cc1)C(C)C(=O)O | -3.70 |
| BadMolecule | INVALID_SMILES | -2.50 |

## Sample Output
```
========================================
CSV CHEMICAL PARSER — Suraj Gade
========================================
Total    : 6
Valid    : 5
Invalid  : 1
Avg MW   : 148.52
Avg LogP : 1.83
========================================
Complete! Output: cleaned_molecules.csv
========================================
```
## What I Learned
- Reading and processing chemical datasets with Pandas
- Validating SMILES strings using RDKit
- Extracting molecular properties programmatically
- Cleaning and filtering invalid chemical data
- Saving processed data to CSV files
- Writing reusable Python functions
- How MolFromSmiles returns None for invalid SMILES
- How to filter DataFrame rows using conditions
