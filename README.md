

# Data Analysis Projects

This repository contains two data analysis projects: one focusing on NYPD data and the other on COVID-19 data. Both projects utilize R for data manipulation, analysis, and visualization.

## Projects Overview

### 1. NYPD Data Analysis

This project analyzes NYPD data to uncover trends and insights related to crime in New York City.

#### Libraries Used

- Tidyverse
- Lubridate

#### Data Import

The following CSV files are imported for analysis:

- `NYPD_Shooting_Incident_Data__Historic_csv`
#### Data Tidying and Transformation

- Removed unnecessary columns.
- Created New Columns such as Day/Night
- New columns for Day / Month / Year
- fixed the object type of some variables such as occur_time and occur_data by using the lubridate mutate function
#### Data Summary

- Filtered out irrelevant observations.
- Summarized the data to include only relevant observations.

#### Data Visualization

- Visualized crime trends over time.
- Analyzed crime distribution by borough and precinct.

### 2. COVID-19 Data Analysis

This project analyzes COVID-19 data to understand the spread and impact of the pandemic globally and in the US.

#### Libraries Used

- Tidyverse
- Lubridate

#### Data Import

The following CSV files are imported for analysis:

- `time_series_covid19_confirmed_US.csv`
- `time_series_covid19_confirmed_global.csv`
- `time_series_covid19_deaths_US.csv`
- `time_series_covid19_deaths_global.csv`
- `UID_ISO_FIPS_LookUp_Table.csv`

#### Data Tidying and Transformation

- Removed unnecessary columns.
- Transformed date columns into a single `date` column.
- Created new columns for analysis, such as `cases` and `deaths`.

#### Data Summary

- Filtered out observations with zero cases.
- Summarized the data to include only relevant observations.

#### Data Visualization

- Visualized cases and deaths over time.
- Summarized total cases and deaths by state and country.

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Run the R scripts to reproduce the analysis and visualizations for both projects.

## Summary Statistics

### NYPD Data

- Key insights and trends related to crime in NYC.

### COVID-19 Data

- Last date in the dataset: `2023-03-09`
- Maximum number of cases: `103,802,702`
- Maximum number of deaths: `1,123,836`

---
