📊 Breast Cancer Dataset Analysis
This Jupyter Notebook performs Exploratory Data Analysis (EDA) and preprocessing on a breast cancer dataset. The objective is to understand the data distribution, identify patterns, and prepare the dataset for machine learning tasks such as classification.

✅ Key Steps Performed:
1. Data Import and Overview
The dataset is loaded from a CSV file.

Basic structure and contents are checked using .head(), .tail(), .info(), and .describe().

Initial shape and summary statistics are reviewed.

2. Data Cleaning
The unnecessary id column is dropped.

Diagnosis values 'M' and 'B' are replaced with 'malignant' and 'benign' for clarity.

3. Missing Values
The dataset is checked for missing values using .isnull().sum().

4. Data Distribution
Diagnosis distribution is visualized using a Seaborn countplot.

Features like radius_mean are plotted using histograms with hue to distinguish between benign and malignant cases.

5. Value Counts
All categorical and numerical columns are analyzed for value distribution using .value_counts().

📈 Visualizations Used
Countplot for diagnosis type distribution

Histogram for comparing radius means across diagnosis categories

More plots likely follow further in the notebook for feature correlation, boxplots, or heatmaps

