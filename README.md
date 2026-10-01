# Unemployment Analysis

## Project Overview

This project was completed as part of the CodeAlpha Data Science Internship.

The objective is to analyze unemployment-rate data, identify trends and
patterns, compare rural and urban observations, examine regional differences,
and analyze changes during the March-June 2020 period.

## Dataset

The dataset contains 768 observations and 7 columns.

After removing rows with missing values, 740 complete observations were used
for the analysis.

Main variables include:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## Data Cleaning

The dataset contained 28 missing values in each column.

Rows containing missing values were removed, resulting in 740 complete
observations.

The column names were also standardized by removing leading and trailing
whitespace.

The Date column was converted to datetime format for time-series analysis.

## Exploratory Data Analysis

The following analyses were performed:

- Overall unemployment trend over time
- Average unemployment rate by area
- Average unemployment rate by region
- COVID-19 period comparison
- Monthly unemployment-rate pattern

## Key Findings

- The average unemployment rate was relatively stable during 2019 and the
  first two months of 2020.
- The average unemployment rate increased from 10.70% in March 2020 to
  23.64% in April 2020.
- The highest monthly average unemployment rate in the dataset was 24.88%
  in May 2020.
- The rate decreased to 11.90% in June 2020.
- The average unemployment rate before March 2020 was 9.51%.
- The average unemployment rate from March to June 2020 was 17.77%.
- Urban observations had an average unemployment rate of 13.17%.
- Rural observations had an average unemployment rate of 10.32%.
- Unemployment rates varied across the regions represented in the dataset.

These findings describe patterns observed in the dataset and do not by
themselves establish causal relationships.

## Results

The analysis results are stored in the `results` folder:

- `monthly_unemployment.csv`
- `unemployment_by_area.csv`
- `unemployment_by_region.csv`
- `covid_comparison.csv`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

text
CodeAlpha_Unemployment_Analysis/
│
├── data/
│ └── Unemployment_Rate.csv
│
├── notebooks/
│ └── unemployment_analysis.ipynb
│
├── results/
│ ├── covid_comparison.csv
│ ├── monthly_unemployment.csv
│ ├── unemployment_by_area.csv
│ └── unemployment_by_region.csv
│
├── README.md
└── requirements.txt
