# ReturnLoop – Data Cleaning and Preprocessing

## Week 2: Data Collection, Cleaning and Preprocessing

This stage prepares the ReturnLoop e-commerce returns dataset for further analysis and predictive modelling.

## Dataset

- Records: 5,000 orders
- Variables: 23
- Granularity: One row per order
- Domain: E-commerce returns and reverse logistics

The dataset contains order, customer, shipping, return, financial and sustainability-related variables.

## Data Quality Checks

The following checks were performed:

- Missing-value assessment
- Duplicate detection
- Data-type validation
- Categorical data validation
- Reverse-logistics business-rule validation
- Outlier detection using the IQR method

## Key Results

- Missing values: 0
- Duplicate rows: 0
- Business-rule violations: 0
- Order_Date successfully converted to datetime
- Potential outliers were identified and retained because they were not confirmed as data errors

## Preprocessing

The following preprocessing techniques were applied:

- One-hot encoding for categorical predictor variables
- Standardisation of numerical variables using StandardScaler
- Separation of the human-readable cleaned dataset from the model-ready processed dataset

One-hot encoding increased the feature set from 23 to 132 columns.

## Outputs

The cleaned dataset retains the original 23-column business structure and is intended for reporting and exploratory analysis.

The processed dataset is encoded and standardised for future predictive modelling.

## Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Week 2 Workflow

Data Collection
→ Data Quality Assessment
→ Missing Value Check
→ Duplicate Check
→ Data Type Validation
→ Business Rule Validation
→ Outlier Detection
→ Encoding
→ Standardisation
→ Validation
→ Model-Ready Data

## Project

ReturnLoop – Reverse Logistics and E-Commerce Returns
