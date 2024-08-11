# SSB_AUTOMATIONS_AI-ML_TASK-1

**Data Collection and Preprocessing**

**1. Collect a Dataset:**

> Obtained the IBM Telco Customer Churn dataset from a public source.

**2. Clean the Data:**

> **Handling Missing Values:**
>> Dropped rows with missing target values (Churn).

>> Converted the TotalCharges column to numeric, filling any resulting NaN values with the mean.

>> Filled missing values in other numeric columns with the mean.

>> Filled missing values in non-numeric columns with the mode (most frequent value).

> **Removing Duplicates:**

>> Removed any duplicate rows to ensure data integrity.

> **Standardizing Formats:**

>> Standardized string formats to lowercase for consistency across categorical columns.

**3. Split the Data:**

> Defined features (X) and target (y), dropping the customerID and Churn columns from features.

> Converted categorical variables to dummy variables (one-hot encoding).

> Split the data into training and test sets using an 80-20 split ratio to prepare for model training and evaluation.
