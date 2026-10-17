# Unemployment Analysis

## Project Overview

This project analyzes unemployment data to understand changes in unemployment rates over time, differences between urban and rural areas, and unemployment trends during the COVID-19 period in India.

This project was completed as part of the CodeAlpha Data Science Internship.

## Objectives

- Clean and prepare unemployment data for analysis.
- Explore unemployment trends over time.
- Compare unemployment rates across regions.
- Analyze differences between urban and rural areas.
- Compare unemployment rates before and during the COVID-19 period.
- Generate visualizations and save analytical results.

## Dataset

The project uses `Unemployment_Rate.csv`, which contains 768 rows and seven columns:

- `Region`
- `Date`
- `Frequency`
- `Estimated Unemployment Rate (%)`
- `Estimated Employed`
- `Estimated Labour Participation Rate (%)`
- `Area`

The dataset contains missing values. After removing rows with missing data, **740 rows** remained for analysis. The recorded date range is May 2019 to June 2020.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methodology

1. Load the dataset using Pandas.
2. Clean column names, convert dates to datetime format, and remove rows with missing values.
3. Examine unemployment rates using summary statistics and visualizations.
4. Calculate monthly average unemployment rates to identify changes over time.
5. Compare unemployment rates across regions.
6. Analyze differences between urban and rural unemployment rates.
7. Compare average unemployment before March 2020 with the March–June 2020 period.
8. Save analytical summaries as CSV files.

## Key Findings

### 1. Urban vs. Rural Unemployment

| Area  | Average Unemployment Rate |
| ----- | ------------------------: |
| Urban |                    13.17% |
| Rural |                    10.32% |

The average unemployment rate was higher in urban areas than in rural areas in the analyzed dataset.

### 2. Before and During the COVID-19 Period

| Period            | Average Unemployment Rate |
| ----------------- | ------------------------: |
| Before March 2020 |                     9.51% |
| March–June 2020   |                    17.77% |
| Difference        |   +8.26 percentage points |

The average unemployment rate increased by approximately **8.26 percentage points** between the two periods.

This is a descriptive comparison and does not independently establish that COVID-19 was the sole cause of the increase.

### 3. Monthly Unemployment Trend

| Month      | Average Unemployment Rate |
| ---------- | ------------------------: |
| March 2020 |                    10.70% |
| April 2020 |                    23.64% |
| May 2020   |                    24.88% |
| June 2020  |                    11.90% |

May 2020 had the highest monthly average unemployment rate in the analyzed period.

## Results

The following files contain the exported analysis:

- `results/covid_comparison.csv` — comparison of the two periods.
- `results/monthly_unemployment.csv` — monthly unemployment averages.
- `results/unemployment_by_area.csv` — unemployment statistics by area.
- `results/unemployment_by_region.csv` — unemployment statistics by region.

The notebook includes visualizations of monthly trends, regional differences, and urban-rural unemployment.

## Conclusion

This analysis highlights important patterns in unemployment data, including regional differences, higher average unemployment in urban areas, and a sharp increase in unemployment during April and May 2020. Data cleaning, exploratory analysis, and visualization help turn raw data into interpretable findings.

## Author

**EBENEZER DABIRE**

GitHub: https://github.com/EBEN-DATASCIENTIST1
