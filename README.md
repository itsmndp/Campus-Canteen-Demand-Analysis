# Campus Canteen Demand Analysis

**Data Mining and Analytics (DMA) Lab Project**

**National Institute of Technology Jalandhar**

## 1. Project Overview

Campus Canteen Demand Analysis is a data mining project developed using R to study food consumption patterns and demand across three campus food outlets:

- Campus Canteen (Snackers)
- Domino's
- Nescafe

The project uses real survey data collected from students and canteen owners to understand food preferences, visiting frequency, spending habits, waiting times, peak demand periods, and inventory-related challenges.

The objective is to extract meaningful insights from survey data and provide practical recommendations that can help canteen owners improve food preparation, stock planning, and customer service.

## 2. Objectives

- Analyze students' food preferences and visiting patterns.
- Identify popular canteens and factors influencing student choices.
- Study spending habits and waiting times.
- Identify peak hours, busy days, and frequently sold-out items.
- Apply data mining techniques to discover patterns and relationships.
- Generate useful recommendations for demand and inventory management.

## 3. Dataset Description

The project uses two datasets collected through Google Forms.

### Student Survey Dataset

Contains information related to:

- Campus residence
- Frequency of visiting different canteens
- Favourite food outlet
- Average spending per visit
- Preferred visiting times
- Waiting times
- Reasons for choosing a particular canteen
- Suggested improvements and new food items

### Canteen Owner Survey Dataset

Contains information related to:

- Approximate daily customer count
- Peak operating hours and busiest days
- Best-selling food items
- Items that frequently sell out
- Unsold inventory
- Food preparation and stock management practices

The datasets are cleaned and processed before analysis.

## 4. Tools and Technologies

- **Programming Language:** R
- **Development Environment:** RStudio
- **Data Collection:** Google Forms
- **Data Processing:** R data frames and data cleaning operations
- **Visualization:** ggplot2 and other R visualization libraries
- **Data Mining:** Statistical analysis, correlation analysis, and K-means clustering

## 5. Methodology

The project follows a structured data mining workflow.

### Step 1: Data Collection

Primary data was collected through separate student and canteen owner surveys.

### Step 2: Data Preprocessing

Raw survey responses were prepared for analysis through:

- Handling missing values
- Cleaning inconsistent responses
- Standardizing categorical values
- Converting numerical columns into suitable data types
- Preparing student and owner datasets for analysis

### Step 3: Exploratory Data Analysis

Exploratory analysis was performed to understand:

- Canteen popularity and visiting frequency
- Student spending distributions
- Waiting time patterns
- Factors affecting canteen selection
- Peak hours and days
- Best-selling and frequently unavailable items

### Step 4: Data Mining Techniques

**Correlation Analysis**

Used to examine relationships between numerical variables such as spending, waiting time, and visiting frequency.

**K-Means Clustering**

Applied to numerical student survey features to identify groups with similar consumption and visiting behaviour.

**Descriptive Statistical Analysis**

Used to summarize survey responses and compare demand patterns across the three outlets.

### Step 5: Data Visualization

Different graphical techniques were used to present the findings clearly:

- Bar charts
- Grouped bar charts
- Histograms
- Boxplots
- Stacked bar charts
- Correlation heatmaps
- Clustering visualizations

### Step 6: Demand Insights and Recommendations

Based on the observed patterns, practical recommendations were developed for improving food availability, stock preparation, and service during peak periods.

## 6. Project Structure

```text
Campus-Canteen-Demand-Analysis/
│
├── Campus_Canteen_DMA.R
├── README.md
│
└── data/
    ├── student_survey.csv
    └── owner_survey.csv
```

The CSV filenames above are suggested names and should match the actual files used by the script.

## 7. How to Run the Project

### Prerequisites

- R installed on your system
- RStudio (recommended)
- Required R packages used in the script

### Execution Steps

1. Clone or download the GitHub repository.
2. Open the project folder in RStudio.
3. Open `Campus_Canteen_DMA.R`.
4. Install any missing R packages required by the script.
5. Ensure the dataset file paths point to the correct CSV files.
6. Run the script.
7. View the generated graphs and analytical results in RStudio.

The visualizations are displayed during execution and can be used to interpret survey findings.

## 8. Expected Outcomes

The project aims to provide:

- A comparative understanding of student demand across the three canteens.
- Insights into spending habits and visiting frequency.
- Identification of important factors influencing canteen preferences.
- Better understanding of busy periods and potential stock shortages.
- Student segmentation based on similar behavioural characteristics.
- Data-driven suggestions for improving food preparation and inventory planning.

## 9. Limitations

- The analysis is based on survey responses rather than complete transaction records.
- Owner-reported demand estimates may differ from actual sales.
- Survey responses represent a limited collection period.
- Recommendations indicate potential improvements rather than guaranteed outcomes.

## 10. Future Scope

The project can be extended in several ways:

- **Real-time Sales Analysis:** Integrate actual daily sales records for more accurate demand estimation.
- **Demand Forecasting:** Use historical sales data and machine learning models to predict future demand.
- **Interactive Dashboard:** Develop a dashboard through Shiny for owners to monitor demand trends.
- **Inventory Optimization:** Suggest stock quantities based on observed consumption patterns.
- **Seasonal Analysis:** Study how examinations, holidays, weather, and campus events influence food demand.
- **Continuous Data Collection:** Collect data across multiple semesters to identify long-term trends.

## 11. Conclusion

The Campus Canteen Demand Analysis project demonstrates how data mining and statistical analysis can be applied to everyday campus operations.

By combining student preferences with owner-reported demand information, the project provides a clearer understanding of food consumption behaviour and operational challenges.

The findings can support better decisions related to food preparation, inventory management, and overall student satisfaction.

---

**Developed as part of the Data Mining and Analytics Laboratory, NIT Jalandhar.**
