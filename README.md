# Healthcare EDA - Exploring Patient, Disease, Insurance, and Medication Data

This project performs an **Exploratory Data Analysis (EDA)** on a healthcare dataset to identify key patterns and relationships between various factors such as patient demographics, diseases, insurance coverage, and medication usage. The objective is to uncover insights that can help improve healthcare outcomes, optimize insurance coverage, and guide medication prescribing practices.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Objective](#objective)
4. [Libraries Used](#libraries-used)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Analysis and Results](#analysis-and-results)
8. [Visualizations](#visualizations)
9. [Conclusion](#conclusion)
10. [License](#license)

## Project Overview

The goal of this project is to explore patterns in healthcare data with the following focus areas:
- **Patient Demographics**: Investigating how characteristics like age, gender, and location relate to disease prevalence.
- **Diseases**: Understanding the relationship between various diseases and how they correlate with patient profiles.
- **Insurance**: Examining how insurance status affects patient care, including medication prescriptions and disease diagnoses.
- **Medications**: Analyzing medication usage patterns across different diseases and patient demographics.

By performing this EDA, we aim to discover insights that can inform healthcare policy, insurance strategies, and medical practices.

## Dataset

The dataset used in this project includes the following columns:
- **Patient Demographics**: Age, gender, location (e.g., urban/rural).
- **Disease Information**: Disease types or conditions diagnosed in patients (e.g., diabetes, hypertension).
- **Insurance**: Patient’s insurance status (insured/uninsured) and insurance type (private/public).
- **Medication**: Medications prescribed to the patients (e.g., antihypertensive, insulin).

The dataset is pre-processed for missing values, and categorical variables are encoded for analysis.

## Objective

The primary objectives of this EDA are:
1. **Analyze patient demographics** and their correlation with the type and frequency of diseases.
2. **Examine disease types** and understand their relationship with prescribed medication.
3. **Investigate insurance status** and its impact on healthcare access, particularly medication prescriptions.
4. **Identify patterns** in medication usage across different patient profiles and disease conditions.

## Libraries Used

### Data Manipulation:
- **pandas**: For efficient data handling, cleaning, and transformation.
- **numpy**: For numerical operations and handling arrays.

### Data Visualization:
- **matplotlib**: For creating visualizations such as bar charts, histograms, and line plots.
- **seaborn**: For advanced visualizations like heatmaps, pair plots, and correlation matrices.

### Statistical Analysis:
- **scipy**: For performing statistical tests and hypothesis testing.

### Machine Learning (Optional for Predictive Insights):
- **scikit-learn**: For potential modeling, classification, and regression tasks.

## Installation

To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/healthcare-eda.git
   cd healthcare-eda
2. Install the required dependencies:

## Usage

1. Load the dataset and explore basic statistics:
2. Visualize correlations between patient demographics and disease types:
3. Generate insights about insurance status and its effect on healthcare outcomes:

## Analysis

The following analyses are performed:
- **Data Cleaning**: Handling missing values, duplicate data, and data type conversions.
- **Descriptive Statistics**: Analyzing the distribution of patient age, disease occurrences, and medication usage.
- **Correlation Analysis**: Identifying correlations between patient characteristics, disease types, medication usage, and insurance status.
- **Visualizations**: Various plots such as histograms, bar plots, box plots, and heatmaps to illustrate key insights.

## Conclusion

The findings from this EDA will help healthcare providers, insurance companies, and policymakers better understand healthcare trends, patient demographics, disease patterns, and medication usage. The goal is to identify areas where interventions or improvements can be made to optimize patient care and insurance coverage.

## License
MIT License
