# Women Safety Crime Analytics in India

An end-to-end Big Data Analytics and Business Intelligence project analyzing crime patterns against women across different regions and time periods in India.

The project uses Python for data preprocessing and transformation, MongoDB Compass for data storage and validation, and Microsoft Power BI for interactive data visualization and analytical dashboards.

## Project Overview

Women safety is an important social and public-safety concern. Raw crime datasets can contain inconsistencies, different formats, and multiple geographical and temporal dimensions, making direct analysis difficult.

This project transforms and analyzes women-related crime datasets to identify:

- Regional crime patterns
- State-wise and district-wise crime distributions
- Crime-prone areas
- Crime-type distributions
- Risk levels
- Day and night crime patterns
- Monthly crime patterns
- Year-wise crime trends
- Geographic crime hotspots
- Comparative crime patterns across areas

The project follows an end-to-end analytics workflow:

Raw Data → Data Preprocessing → Data Validation → MongoDB Compass → Power BI → Interactive Dashboards → Insights

## Objectives

The main objectives of the project are:

1. Clean and standardize crime-related datasets.
2. Transform datasets into structured analytical formats.
3. Analyze crime patterns across locations and time periods.
4. Identify high-risk and crime-prone areas.
5. Analyze crime categories and their distributions.
6. Examine day/night and monthly crime patterns.
7. Develop interactive dashboards for data exploration.
8. Present analytical insights through effective data visualization.

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- MongoDB Compass
- Microsoft Power BI
- Power Query
- DAX
- CSV datasets

## Data Processing

Python was used for data preprocessing and preparation.

The preprocessing workflow included:

- Loading multiple crime datasets
- Standardizing column names
- Cleaning and validating data
- Handling missing and inconsistent values
- Transforming datasets into analytical formats
- Filtering relevant crime categories
- Preparing cleaned datasets for database storage and visualization

Pandas and NumPy were used for data manipulation and numerical operations.

## MongoDB Compass

MongoDB Compass was used for data storage, inspection, validation, filtering, sorting, and aggregation.

The analysis included operations such as:

- Crime count by area
- Most common crime types
- Day versus night crime analysis
- Crime analysis by hour
- Crime analysis by weekday
- Crime analysis by risk level
- State and district-level aggregation
- Year and crime-type aggregation

## Power BI Dashboard

Power BI was used to build interactive dashboards for exploratory and descriptive analytics.

The dashboards include:

### Executive Overview

- Total crimes
- High-risk incidents
- Crime types
- Areas covered
- Top crime-prone areas
- Crime type distribution

### Geographic and Risk Analysis

- Crime hotspot maps
- State-wise crime analysis
- Unsafe city/area analysis
- Crime severity levels
- Women safety risk zones
- Geographic risk visualization

### Temporal and Crime Analysis

- Monthly crime patterns
- Day versus night crime comparison
- Crime trends across years
- Crime-type analysis
- Area-wise crime comparison
- Risk-level analysis
- Comparative visualizations

## Dashboard Screenshots

### Executive Overview

![Executive Overview](images/Executive%20Overview.png)

### Geographic & Risk Analysis

![Geographic & Risk Analysis](images/Geographic%20%26%20Risk%20Analysis.png)

### Temporal & Forecast Analysis

![Temporal & Forecast Analysis](images/Temporal%20%26%20Forecast%20Analysis.png)

## Project Structure

```text
women-safety-crime-analytics-india/
│
├── README.md
│
├── dashboard/
│   └── women_safety_dashboard.pbix.pbix
│
├── notebooks/
│   ├── BDA proj data.ipynb
│   ├── combine data.ipynb
│   ├── crime data.ipynb
│   └── crime_data_analysis.ipynb.ipynb
│
├── data/
│   ├── final_crime_dataset_1.csv
│   ├── final_event_level_dataset.csv
│   ├── final_aggregated_district_dataset.csv
│   ├── final_ncrb_women_crimes.csv
│   ├── final_indicator_dataset.csv
│   ├── final_women_children_crimedata_cleaned.csv
│   ├── final_outdoor_women_crimes_2017_normalized.csv
│   └── final_women_outdoor_crimes_2024.csv
│
└── images/
    ├── Executive Overview.png
    ├── Geographic & Risk Analysis.png
    └── Temporal & Forecast Analysis.png
