# Credit Card Behavioral Analysis — Colab Implementation

## Overview

This project provides a comprehensive analysis of credit card transaction data to:
- Understand customer spending behaviors
- Identify hidden patterns
- Detect anomalies
- Segment customers into distinct behavioral groups

The analysis is implemented in Google Colab using Python and widely used data science libraries.

---

## Key Features

- **Data Exploration:** Initial assessment of data quality and structure  
- **Feature Engineering:** Creation of meaningful behavioral features  
- **Customer Segmentation:** K-means clustering to identify distinct customer groups  
- **Anomaly Detection:** Isolation Forest to flag unusual spending patterns  
- **Behavioral Analysis:** Examination of spending patterns across time, categories, and demographics  
- **Visual Dashboard:** Comprehensive visualizations of key insights  

---

## Data Requirements
Dataset Link: [Credit cards dataset](https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset)
The analysis expects a CSV file named `credit_card_transactions.csv` with columns such as:

- **Transaction Details:** `trans_date_trans_time`, `cc_num`, `amt`, `category`
- **Customer Details:** `gender`, `dob`, `job`, `city_pop`, `state`
- **Location Data:** `lat`, `long`, `merch_lat`, `merch_long`

---

## Implementation

The analysis is structured across 16 Colab cells:

1. **Setup:** Import libraries and configure settings  
2. **Data Loading:** Load data and perform initial exploration  
3. **Data Quality:** Assess missing values and duplicates  
4. **Preprocessing:** Clean data and create new features  
5–6. **Univariate Analysis:** Examine individual variables  
7. **Bivariate Analysis:** Explore relationships between variables  
8. **Outlier Detection:** Identify unusual transactions  
9. **Data Cleaning:** Handle missing values and duplicates  
10. **Customer Profiles:** Create aggregated behavioral profiles  
11. **Segmentation:** K-means clustering of customers  
12. **Spending Patterns:** Analyze spending by category, time, etc.  
13. **Anomaly Detection:** Identify unusual customer behaviors  
14. **Business Insights:** Generate actionable recommendations  
15. **Visual Dashboard:** Visualize key findings  
16. **Summary:** Export results and final insights  

---

## Key Outputs

The analysis generates several important outputs:

- Cleaned dataset: `credit_card_transactions_cleaned.csv`
- Customer behavioral profiles: `customer_behavioral_profiles.csv`
- Identified anomalies: `behavioral_anomalies.csv`
- Spending patterns by category: `spending_patterns_by_category.csv`
- Comprehensive visualization dashboard

---

## Usage

1. Upload your credit card transaction data to Colab as `credit_card_transactions.csv`.  
2. Run all cells sequentially.  
3. Review the generated insights and visualizations.  
4. Download the exported CSV files for further analysis.

---

## Dependencies

This project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Insights Generated

By running this analysis, you will obtain:

- Customer segmentation into five distinct behavioral groups  
- Identification of spending patterns across time and categories  
- Detection of unusual customer behaviors  
- Demographic and geographic spending preferences  
- Temporal patterns in transaction activity

---

## Customization

To adapt this analysis for your specific dataset:

- Adjust column names in the data loading cell if needed  
- Modify the feature engineering steps based on available data  
- Tune clustering parameters for your customer base  
- Adjust anomaly detection sensitivity as needed
