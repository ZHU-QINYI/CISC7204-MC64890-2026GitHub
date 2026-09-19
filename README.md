# CISC7204 — Assignment 01: Data Science Portfolio

**Student:** ZHU QINYI
**Student ID:** MC64890
**Email:** MC64890@um.edu.mo
**Course:** CISC7204
**Repository:** `CISC7204-MC64890-2026GitHub`
**Assignment folder:** `cisc7204-Assgn01-2026-MC64890/`

---

## Overview

This repository contains my Assignment 01 submission for **CISC7204**. The work covers
the full introductory data-science workflow — from loading and cleaning raw data, through
exploratory data analysis, to building, evaluating and refining regression models.

All work is contained in the folder [`cisc7204-Assgn01-2026-MC64890/`](cisc7204-Assgn01-2026-MC64890),
organised by module. Each module holds its Jupyter notebooks, the datasets used, and a
`screenshot/` folder with the code and output capture for every question and section.

---

## Module Index

| Module | Lab | Notebook | Topic |
|---|---|---|---|
| 01 | Lab 01 | `CISC7204 Assgn01 Module 01 - Lab01 MC64890 ZHU QINYI.ipynb` | Importing Dataset — automobile data |
| 01 | Lab 02 | `CISC7204 Assgn01 Module 01 - Lab02 MC64890 ZHU QINYI.ipynb` | Hands-on Practice: Importing Dataset — Laptops Pricing |
| 02 | Lab 01 | `CISC7204 Assgn01 Module 02 - Lab01 MC64890 ZHU QINYI.ipynb` | Data Wrangling — missing values, binning, indicators |
| 02 | Lab 02 | `CISC7204 Assgn01 Module 02 - Lab02 MC64890 ZHU QINYI.ipynb` | Hands-on Practice: Data Wrangling — Laptops Pricing |
| 03 | Lab 01 | `CISC7204 Assgn01 Module 03 - Lab01 MC64890 ZHU QINYI.ipynb` | Exploratory Data Analysis — correlation & visualisation |
| 03 | Lab 02 | `CISC7204 Assgn01 Module 03 - Lab02 MC64890 ZHU QINYI.ipynb` | Hands-on Lab: Exploratory Data Analysis — Laptops Pricing |
| 04 | Lab 01 | `CISC7204 Assgn01 Module 04 - Lab01 MC64890 ZHU QINYI.ipynb` | Model Development — simple/multiple/polynomial regression |
| 04 | Lab 02 | `CISC7204 Assgn01 Module 04 - Lab02 MC64890 ZHU QINYI.ipynb` | Hands-on Practice: Model Development — Laptops Pricing |
| 05 | Lab 01 | `CISC7204 Assgn01 Module 05 - Lab01 MC64890 ZHU QINYI.ipynb` | Model Evaluation and Refinement — cross-validation & Ridge |
| 05 | Lab 02 | `CISC7204 Assgn01 Module 05 - Lab02 MC64890 ZHU QINYI.ipynb` | Hands-on Practice: Model Evaluation and Refinement |
| 06 | Practice Project | `CISC7204 Assgn01 Module 06 - PracticeProj MC64890 ZHU QINYI.ipynb` | Insurance Cost Analysis |
| 06 | Final Project | `cisc7204C_Assgn01_Mod06FinalProject_MC64890.ipynb` | House Sales in King County — price prediction |

---

## Repository Structure

```
CISC7204-MC64890-2026GitHub/
├── README.md
├── .gitignore
└── cisc7204-Assgn01-2026-MC64890/
    ├── module01/
    │   ├── CISC7204 Assgn01 Module 01 - Lab01 MC64890 ZHU QINYI.ipynb
    │   ├── CISC7204 Assgn01 Module 01 - Lab02 MC64890 ZHU QINYI.ipynb
    │   ├── *.csv / *.db                 # datasets used by the notebooks
    │   └── screenshot/                  # code + output captures per question
    ├── module02/
    ├── module03/
    ├── module04/
    ├── module05/
    └── module06/
```

---

## Topics Covered

- **Data acquisition** — reading CSV files and querying a SQLite database with `pandas`
- **Data wrangling** — handling missing values, data formatting, normalisation, binning and indicator variables
- **Exploratory data analysis** — descriptive statistics, `groupby`/pivot tables, correlation matrices, `seaborn` visualisations
- **Model development** — simple and multiple linear regression, polynomial regression, `Pipeline` with `StandardScaler`
- **Model evaluation and refinement** — train/test split, cross-validation, overfitting, Ridge regression and `GridSearchCV`

## Datasets

| File | Used in |
|---|---|
| `automobile.csv`, `auto.csv` | Module 01 |
| `laptops.csv`, `laptops_database.csv`, `laptop_prices.db` | Modules 01–05 |
| `usedcars.csv` | Modules 02, 04 |
| `module_5_auto.csv` | Module 05 |
| `housing.csv` | Module 06 Final Project |
| `medical_insurance_dataset.csv` | Module 06 Practice Project |

---

## Running the Notebooks

```bash
python -m pip install jupyter pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

Open any `.ipynb` file from within its own module folder — the notebooks load their
datasets using relative paths.

---

## Screenshots

Each module's `screenshot/` directory contains a PNG capture of the code and its output
for every question and section, named after the module, lab, section/question number and
the operation performed.
