# COVID-19 Global Data Tracker

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-brightgreen)

## Project Overview
A data analysis project tracking COVID-19 cases, deaths, and vaccination progress across multiple countries. The project cleans real-world data, performs exploratory analysis, and visualizes key trends using Python data tools.

## Project Structure
covid19-project/
├── data/ # Raw and cleaned datasets
│ └── owid-covid-data.csv # Primary dataset
├── notebooks/
│ └── covid_analysis.ipynb # Main analysis notebook
├── outputs/ # Generated visualizations
│ ├── cases_plot.png
│ ├── deaths_plot.png
│ └── vaccinations_plot.png
└── README.md # This file


## Key Features
- Data cleaning and preprocessing pipeline
- Time-series analysis of cases/deaths
- Vaccination progress comparison
- Interactive choropleth maps
- Country-specific trend analysis

## Requirements
```text
Python 3.11+
Jupyter Notebook
pandas >= 2.0
matplotlib >= 3.7
seaborn >= 0.12
plotly >= 5.15

## Installation
Clone the repository:
git clone https://github.com/yourusername/covid19-analysis.git
cd covid19-analysis

Install dependencies:
pip install -r requirements.txt  # Or use the packages listed above

Usage
Run the Jupyter notebook:
jupyter notebook notebooks/covid_analysis.ipynb

Execute cells sequentially to:

Load and clean data

Generate visualizations

Export analysis results

Key Analysis Sections
Data Loading & Cleaning

Handles missing values

Converts date formats

Filters key countries

Trend Analysis

Case/death progression

Peak infection periods

Vaccination rollout

Comparative Analysis

Country-wise performance

Death rate calculations

Vaccination coverage

Viewing Results
For best viewing:

Open the notebook in Jupyter nbviewer

Or launch in Google Colab

Insights Summary
Vaccination rates correlate with...

Highest death rates observed in...

Case spikes occurred during...

License
MIT License
