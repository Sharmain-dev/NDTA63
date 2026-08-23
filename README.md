# README.md – NDTA631 Data Analysis and Visualization Project

## Project Overview

This repository contains the Group Assignment for **NDTA631 – Data Analysis and Visualization** (Diploma in ICT).

The project analyses two South African World Bank datasets to investigate the relationship between **Antiretroviral Therapy (ART) Coverage** and **Under-5 Mortality Rates** in South Africa. The analysis follows a complete data analytics pipeline, including data cleaning, numerical analysis, visualization, database integration, and reporting.

## Group Members

Gontlafetse Sebati 202329436(Group Leader)
Hopewell Ramadwa 202308192
Tshegofatso Kemisho 202104512
Dimpho Sharmain Maenetja 202436296
Sello Mpho 202324276
Tebogo Kobe 202403949 


## Datasets Used

### Dataset 1: ART Coverage

Measures the percentage of people receiving Antiretroviral Therapy (ART) in South Africa.

### Dataset 2: Under-5 Mortality

Measures the mortality rate of children under five years of age in South Africa.

**Source:** World Bank Open Data (South Africa)

## Project Objectives

* Load and clean real-world datasets.
* Handle missing values and duplicates.
* Generate descriptive statistics.
* Perform numerical analysis using NumPy.
* Create meaningful visualizations.
* Build and query a SQLite database.
* Export transformed data for reporting.
* Draw conclusions from the data.

## Repository Structure

```text
NDTA631/
│
├── GroupAssignment.ipynb
├── WB_HCP_HVA_PED_ART_CVG.csv
├── WB_WDI_SH_DYN_MORT.csv
├── analysis.db
├── transformed_data.xlsx
├── exported_data.csv
├── README.md
└── Report.pdf
```

## Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib
* SQLite3
* OpenPyXL
* Jupyter Notebook

## Installation

Clone the repository:

```bash
git clone https://github.com/Sharmain-dev/NDTA63.git
cd NDTA63
```

Install required packages:

```bash
pip install pandas numpy matplotlib openpyxl jupyter
```

## Running the Project

1. Ensure all CSV datasets are in the project directory.
2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Open:

```text
GroupAssignment.ipynb
```

4. Run all cells from top to bottom.

## Project Workflow

### 1. Data Preparation

* Imported both datasets.
* Filtered data for South Africa.
* Selected relevant variables.
* Renamed columns for consistency.
* Checked data types.
* Identified missing values.
* Checked duplicate records.
* Sorted data by year.
* Generated descriptive statistics.

### 2. Numerical Analysis

Using NumPy:

* Calculated summary statistics.
* Reshaped arrays.
* Performed array operations.
* Calculated correlation between ART coverage and Under-5 mortality.
* Interpreted numerical findings.

### 3. Data Visualization

The notebook includes:

* Line Chart
* Bar Graph
* Scatter Plot
* Box Plot

These visualizations help identify trends, patterns, and relationships between the two datasets.

### 4. Database Integration

SQLite was used to:

* Create a database.
* Store cleaned datasets.
* Execute SQL queries.
* Perform JOIN operations.
* Demonstrate safe UPDATE operations.
* Demonstrate safe DELETE operations.
* Load query results into Pandas.
* Export results to CSV.

### 5. Python/Excel Analysis

* Cleaned and transformed queried data.
* Exported results to Excel.
* Applied conditional formatting.
* Generated Excel charts.
* Produced summary findings.

## Key Findings

* ART coverage in South Africa generally increased over time.
* Under-5 mortality showed a declining trend.
* Visual and numerical analysis suggest an inverse relationship between ART coverage and child mortality.
* Database queries and statistical analysis supported the observed trends.

## Error Handling

The project includes validation steps such as:

* Missing value checks.
* Duplicate record checks.
* Data type verification.
* Safe SQL parameterized queries.
* Controlled update and delete operations.

## Conclusion

This project demonstrates a complete data analysis pipeline using Python and SQLite. By combining healthcare datasets, the analysis provides insights into health-related trends in South Africa and showcases practical skills in data preparation, analysis, visualization, database management, and reporting.

## Version Control

Git and GitHub were used to manage project versions, track changes, and support collaborative development.

## Authors

NDTA631 Group Assignment Team – 2026

## License

This repository was created for academic purposes as part of the NDTA631 Data Analysis and Visualization module.

## NDTA63 - Data Analysis and Visualization

[![Code License](https://img.shields.io/badge/Code%20License-GPLv2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20%40iammelvink-blue.svg?style=social&logo=linkedin)](https://www.linkedin.com/in/iammelvink)

## Overview

This is the codebase produced for the **NDTA63 Data Analysis and Visualization** course

Written in **Placeholder**

1. Methodologies/Project Management:

   - Agile

2. Coding Practices:

   - OOP (Object Oriented Programming)
   - MVC (Model View Controller)

3. Programming Languages/Frameworks:

   - Placeholder

## Instructions

1. Make sure you have these installed

2. Clone `ONLY THE LATEST COMMIT` of this repository into your local machine using the terminal (mac) or
   [Gitbash (PC)](https://git-scm.com/download/win 'Gitbash (PC)') `to save storage space`

   ```sh
   git clone https://github.com/iammelvink/NDTA63.git --depth=1
   ```

## Author(s)

"Group members and lecturer"

[Melvin Kisten](https://github.com/iammelvink 'Melvin Kisten\'s GitHub page')

GitHub: @"Group members"

LinkedIn: [Melvin Kisten](https://www.linkedin.com/in/iammelvink 'Melvin Kisten\'s LinkedIn page')

## Acknowledgments

To my lecturer [Melvin Kisten](https://www.linkedin.com/in/iammelvink 'Melvin Kisten\'s LinkedIn page') for their guidance

## More Stuff

Check out some other stuff on
[Melvin Kisten](https://github.com/iammelvink 'Melvin Kisten\'s GitHub page')