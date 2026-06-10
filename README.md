# COVID-19 Impact on Unemployment in India: Exploratory Data Analysis

## Project Overview

This project analyzes unemployment trends across India during the COVID-19 pandemic using Exploratory Data Analysis (EDA). The objective is to understand how unemployment changed over time, identify the regions most affected by economic disruptions, compare rural and urban labor markets, and uncover patterns within key employment indicators.

The analysis is based on **740 observations** collected across **28 Indian states and union territories** between **June 2019 and July 2020**.

---

## Business Problem

Unemployment is one of the most important indicators of economic health. The COVID-19 pandemic and nationwide lockdown significantly disrupted economic activity, affecting businesses, industries, and labor markets across India.

This project aims to answer the following questions:

* How did unemployment change before and during COVID-19?
* Which states experienced the highest unemployment rates?
* Which regions were most affected by lockdown-related disruptions?
* How do rural and urban unemployment patterns differ?
* Are there seasonal patterns in unemployment?
* What relationships exist between unemployment, employment, and labor participation?

---

## Dataset Information

### Dataset Summary

| Metric          | Value                     |
| --------------- | ------------------------- |
| Total Records   | 740                       |
| Total Features  | 7                         |
| Regions Covered | 28                        |
| Time Period     | June 2019 – July 2020     |
| Analysis Type   | Exploratory Data Analysis |

### Features Used

| Feature                                 | Description                          |
| --------------------------------------- | ------------------------------------ |
| Region                                  | State/Union Territory                |
| Date                                    | Observation Date                     |
| Frequency                               | Reporting Frequency                  |
| Estimated Unemployment Rate (%)         | Percentage of Unemployed Individuals |
| Estimated Employed                      | Number of Employed Individuals       |
| Estimated Labour Participation Rate (%) | Labor Force Participation Rate       |
| Area                                    | Rural or Urban Classification        |

---

## Project Workflow

### 1. Data Understanding

* Examined dataset structure and data types
* Reviewed feature descriptions
* Verified dataset completeness

### 2. Data Cleaning

* Converted date column into datetime format
* Checked for missing values
* Removed duplicate records
* Standardized column names
* Validated data consistency

### 3. Exploratory Data Analysis

Performed visual and statistical analysis to identify trends, patterns, and anomalies within unemployment data.

---

## Visualizations and Insights

### 1. National Unemployment Trend Analysis

A time-series analysis was conducted to track average unemployment across India.

#### Key Findings

* National unemployment remained relatively stable between **8.9% and 10%** throughout most of 2019.
* The unemployment rate increased dramatically during the COVID-19 lockdown period.
* The highest unemployment level of approximately **24.9%** was recorded in **May 2020**.
* This represents an increase of nearly **180%** compared to the lowest observed unemployment rate of **8.9% in June 2019**.

---

### 2. Regional Trend Comparison

Four states were selected to compare unemployment behavior over time:

* Tripura
* Haryana
* Maharashtra
* Tamil Nadu

#### Key Findings

* Tripura consistently maintained high unemployment levels throughout the study period.
* Haryana also recorded persistently elevated unemployment rates.
* Maharashtra remained comparatively stable before experiencing a COVID-related spike.
* Tamil Nadu experienced one of the sharpest increases during the lockdown period, reaching nearly **50% unemployment** in May 2020.

---

### 3. Distribution of Unemployment Across Regions

Boxplot analysis was used to evaluate variability and spread across states.

#### Key Findings

* Tripura displayed the highest unemployment distribution among all regions.
* Meghalaya maintained the lowest unemployment levels with relatively low variability.
* Several regions showed significant outliers, indicating periods of extreme labor market stress.

---

### 4. COVID-19 Lockdown Impact Analysis

The change in unemployment between **March 2020** and **April 2020** was analyzed to quantify the immediate impact of lockdown restrictions.

#### Most Affected Regions

| Region     | Increase in Unemployment Rate |
| ---------- | ----------------------------- |
| Puducherry | +74 percentage points         |
| Tamil Nadu | +43 percentage points         |
| Jharkhand  | +41 percentage points         |
| Bihar      | +36 percentage points         |
| Karnataka  | +25 percentage points         |

#### Key Findings

* Puducherry experienced the most severe labor market shock.
* Multiple states recorded double-digit increases in unemployment within a single month.
* The economic impact of lockdown measures varied significantly across regions.

---

### 5. Average Unemployment Ranking by Region

Average unemployment rates were calculated for each state across the study period.

#### Highest Average Unemployment

| Rank | Region    | Average Rate |
| ---- | --------- | ------------ |
| 1    | Tripura   | 28.4%        |
| 2    | Haryana   | 26.2%        |
| 3    | Jharkhand | 20.5%        |

#### Lowest Average Unemployment

| Rank | Region    | Average Rate |
| ---- | --------- | ------------ |
| 1    | Meghalaya | 4.8%         |
| 2    | Odisha    | 5.6%         |
| 3    | Assam     | 6.3%         |

#### Key Finding

The difference between the highest and lowest average unemployment rates exceeded **23 percentage points**, highlighting substantial regional disparities in labor market conditions.

---

### 6. Rural vs Urban Unemployment Analysis

Unemployment patterns were compared between rural and urban areas.

#### Key Findings

* Urban unemployment remained consistently higher than rural unemployment.
* During the COVID-19 peak:

  * Urban unemployment reached approximately **28.2%**
  * Rural unemployment reached approximately **21.8%**
* Urban unemployment exceeded rural unemployment by approximately **6–7 percentage points** during the most severe disruption period.

This suggests urban labor markets were more vulnerable to lockdown-related economic shocks.

---

### 7. Seasonal Pattern Analysis

Monthly unemployment averages were analyzed to identify recurring patterns.

#### Key Findings

| Month | Average Unemployment |
| ----- | -------------------- |
| April | 23.6%                |
| May   | 16.6%                |
| June  | 10.5%                |
| July  | 9.0%                 |

* April recorded the highest unemployment level of the entire study period.
* Most non-pandemic months remained close to **9–10% unemployment**.
* The dramatic April spike reflects the immediate economic consequences of nationwide lockdown restrictions.

---

### 8. Correlation Analysis

A correlation matrix was created to evaluate relationships between labor market indicators.

#### Correlation Results

| Variables                            | Correlation |
| ------------------------------------ | ----------- |
| Unemployment vs Employment           | -0.22       |
| Unemployment vs Labour Participation | 0.00        |
| Employment vs Labour Participation   | 0.01        |

#### Interpretation

* A weak negative relationship exists between unemployment and employment levels.
* Labor participation rate showed almost no linear relationship with unemployment.
* Employment and labor participation also exhibited negligible correlation within this dataset.

---

## Key Findings Summary

* The dataset contains **740 observations spanning 14 months and 28 regions**.
* National unemployment peaked at **24.9% in May 2020**.
* Unemployment increased by approximately **180%** compared to pre-pandemic levels.
* **Tripura (28.4%)** recorded the highest average unemployment rate.
* **Meghalaya (4.8%)** recorded the lowest average unemployment rate.
* **Puducherry (+74 percentage points)** experienced the largest unemployment increase following lockdown implementation.
* Urban unemployment exceeded rural unemployment by approximately **6–7 percentage points** during peak disruption.
* Correlation analysis revealed only weak relationships among major labor market indicators.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Time Series Analysis
* Correlation Analysis
* Business Insight Generation
* Data Storytelling

---

## Conclusion

This analysis demonstrates the substantial impact of COVID-19 on India's labor market. While unemployment remained relatively stable throughout 2019, the nationwide lockdown triggered a sharp increase in joblessness across multiple regions. Significant differences were observed between states, with Tripura and Haryana experiencing consistently higher unemployment levels, while Meghalaya and Odisha maintained comparatively lower rates. The analysis also revealed that urban labor markets were more severely affected than rural areas. Overall, the findings highlight the importance of region-specific employment policies and data-driven decision-making during periods of economic uncertainty.

---

## Future Improvements

* Build unemployment forecasting models using machine learning.
* Develop an interactive Power BI dashboard.
* Perform state-level clustering analysis.
* Incorporate additional macroeconomic indicators such as GDP and inflation.
* Create predictive models for post-pandemic employment recovery.
