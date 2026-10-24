# CISC7204 — Assignments 01 & 02: Data Science Portfolio

**Student:** ZHU QINYI
**Student ID:** MC64890
**Email:** MC64890@um.edu.mo
**Course:** CISC7204
**Repository:** `CISC7204-MC64890-2026GitHub`

---

## Assignments

| Assignment | Folder | Scope |
|---|---|---|
| Assignment 01 | [`cisc7204-Assgn01-2026-MC64890/`](cisc7204-Assgn01-2026-MC64890) | Modules 01–06: data acquisition, wrangling, EDA, model development, model evaluation |
| Assignment 02 | [`cisc7204-Assgn02-2026-MC64890/`](cisc7204-Assgn02-2026-MC64890) | Modules 01–05: pandas, plotting, advanced visualisation, Plotly/Dash, final project |

Each assignment folder is organised by module. Each module holds its Jupyter notebooks and a
`screenshot/` folder with the code and output capture for every question and section.

---

# Assignment 01 — Data Science Portfolio

**Folder:** `cisc7204-Assgn01-2026-MC64890/`

## Overview

This assignment covers the full introductory data-science workflow — from loading and cleaning
raw data, through exploratory data analysis, to building, evaluating and refining regression
models.

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

# Assignment 02 — Data Visualisation Portfolio

**Folder:** `cisc7204-Assgn02-2026-MC64890/`

## Overview

This assignment builds a data-visualisation portfolio: it starts from `pandas` fundamentals and
the standard `matplotlib` plotting interface, moves through the full catalogue of static charts
(line, area, histogram, bar, pie, box, scatter, bubble, waffle, word cloud, `seaborn`), then
into interactive visualisation with `folium` maps, `plotly`, and finally **Dash** — building
progressively richer interactive dashboards and finishing with a final project on US wildfire
data.

All notebooks fetch their datasets from public IBM Skills Network URLs, so the folder is
self-contained and needs no local data files.

## Module Index

| Module | Lab | Notebook | Topic |
|---|---|---|---|
| 01 | Lab 01 | `CISC7204 Assgn02 Module 01 - Lab01 MC64890 ZHU QINYI.ipynb` | Pandas Basics — Canada immigration dataset, indexing, filtering, sorting |
| 01 | Lab 02 | `CISC7204 Assgn02 Module 01 - Lab02 MC64890 ZHU QINYI.ipynb` | Matplotlib Basics — line plots, labels, annotations, multi-series trends |
| 02 | Lab 01 | `CISC7204 Assgn02 Module 02 - Lab01 MC64890 ZHU QINYI.ipynb` | Plotting Directly with Matplotlib — area, histogram, bar charts |
| 02 | Lab 02 | `CISC7204 Assgn02 Module 02 - Lab02 MC64890 ZHU QINYI.ipynb` | Pie, box, scatter and bubble plots; subplots |
| 02 | Lab 03 | `CISC7204 Assgn02 Module 02 - Lab03 MC64890 ZHU QINYI.ipynb` | Plotting with Matplotlib — full chart catalogue & subplotting |
| 03 | Lab 01 | `CISC7204 Assgn02 Module 03 - Lab01 MC64890 ZHU QINYI.ipynb` | Waffle charts, word clouds, `seaborn` categorical & regression plots |
| 03 | Lab 02 | `CISC7204 Assgn02 Module 03 - Lab02 MC64890 ZHU QINYI.ipynb` | Generating Maps with `folium` — choropleths, markers, marker clusters |
| 04 | Lab 01 | `CISC7204 Assgn02 Module 04 - Lab01 MC64890 ZHU QINYI.ipynb` | Basic `plotly` charts — scatter, line, bar, histogram, bubble, pie, sunburst |
| 04 | Lab 02 | `CISC7204 Assgn02 Module 04 - Lab02 MC64890 ZHU QINYI.ipynb` | Dash Basics — airline on-time performance dashboard |
| 04 | Lab 03 | `CISC7204 Assgn02 Module 04 - Lab03 MC64890 ZHU QINYI.ipynb` | Dash Interactivity — callbacks, inputs, chart switching |
| 04 | Lab 04 | `CISC7204 Assgn02 Module 04 - Lab04 MC64890 ZHU QINYI.ipynb` | Flight Delay Time Statistics Dashboard — five linked line charts |
| 05 | Practice Project | `CISC7204 Assgn02 Module 05 - PracticeProjLab01 MC64890 ZHU QINYI.ipynb` | Historical wildfires — interactive Dash wildfire reporting tool |
| 05 | Final Project | `CISC7204 Assgn02 Module 05 - FinalProjLab01 MC64890 ZHU QINYI.ipynb` | Automobile sales — Dash final project dashboard |

## Dash Applications

| File | Module | Description |
|---|---|---|
| `dash_basics.py` | 04 | Airline on-time performance — basic layout and pie chart |
| `dash_interactivity.py` | 04 | Airline performance — year input driving a delay line chart |
| `dash_interactivity_barplot.py` | 04 | Flights by destination state, split by reporting airline (bar chart) |
| `flight_details.py` | 04 | Flight delay statistics — five `px.line` charts in one dashboard |
| `Dash_wildfire.py` | 05 | Wildfire reporting tool — interactive dashboard on historical wildfire data |
| `DV0101EN-Final-Assign-Part-2-Questions.py` | 05 | Final project — automobile sales dashboard |

Run any of them with:

```bash
python dash_basics.py     # then open http://127.0.0.1:8050
```

## Topics Covered

- **`pandas` fundamentals** — loading, indexing, filtering, sorting, `groupby`
- **`matplotlib`** — line, area, histogram, bar, pie, box, scatter and bubble plots; subplots; annotations
- **Advanced static visualisation** — waffle charts, word clouds, `seaborn` categorical and regression plots
- **Geospatial** — `folium` choropleth maps, markers, popups and marker clusters
- **Interactive visualisation** — `plotly` graph objects and `plotly.express`
- **Dash** — layout, components, callbacks, multi-chart dashboards and reusable helper functions

---

## Repository Structure

```
CISC7204-MC64890-2026GitHub/
├── README.md
├── .gitignore
├── cisc7204-Assgn01-2026-MC64890/
│   ├── module01/ … module06/
│   │   ├── *.ipynb                    # lab notebooks
│   │   ├── *.csv / *.db               # datasets used by the notebooks
│   │   └── screenshot/                # code + output captures per question
└── cisc7204-Assgn02-2026-MC64890/
    ├── module01/
    │   ├── *.ipynb
    │   └── Screen shot/               # code + output captures per question
    ├── module02/
    ├── module03/
    ├── module04/                      # notebooks + Dash applications
    └── module05/                      # final project notebooks + Dash applications
```

---

## Running the Notebooks

```bash
python -m pip install jupyter pandas numpy matplotlib seaborn scikit-learn plotly dash folium pywaffle wordcloud
jupyter notebook
```

Open any `.ipynb` file from within its own module folder.

---

## Screenshots

Each module's screenshot directory contains a PNG capture of the code and its output for every
question and section, named after the lab, the section/question number and the operation
performed (the module is given by the containing folder).

> **Note on filenames:** the screenshot names deliberately omit the `CISC7204 Assgn0N Module NN`
> prefix. Including it pushed several paths past 230 characters, which exceeds the Windows
> `MAX_PATH` limit of 260 and breaks `git clone` in most locations.
