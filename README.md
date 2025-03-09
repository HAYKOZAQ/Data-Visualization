# Data Visualization : Customer Churn Analysis
# First part: Exploratory Data Analysis (EDA)
##  Overview
This project focuses on performing an **Exploratory Data Analysis (EDA)** on a customer churn dataset to gain insights into factors driving customer retention and attrition. The dataset comprises 21 columns, capturing customer demographics, service usage, billing information, and churn status, providing a rich basis for identifying patterns that can inform strategies to reduce churn.

## What I Have Done
I conducted a thorough EDA to explore the dataset and uncover actionable insights. Key steps include:

- **Initial Data Inspection**: Examined the dataset structure, checking for missing values, duplicates, and data types to understand its quality and characteristics.
- **Data Cleaning**:
  - Handled missing values by converting `TotalCharges` to numeric and imputing with `MonthlyCharges * tenure` where applicable.
  - Removed duplicates based on `customerID` to ensure unique entries.
  - Ensured consistent data types (e.g., `Churn` as binary 0/1, `SeniorCitizen` as integer).
- **Basic Analysis**:
  - Analyzed churn rates across categorical features (e.g., `Contract`, `InternetService`) using bar plots.
  - Explored numerical features (e.g., `tenure`, `MonthlyCharges`) with histograms and box plots.
- **Advanced Techniques**:
  - Applied dimensionality reduction methods like Principal Component Analysis (PCA), Multidimensional Scaling (MDS), and t-SNE to reveal latent structures, visualized via scatter plots.
- **Feature Interactions**:
  - Investigated relationships between variables (e.g., `TechSupport` and `Contract`, `PaymentMethod` and `TenureSegment`) using grouped bar plots, line plots, and heatmaps.
- **Derived Features**:
  - Created new features such as `NumAddons` and `ChargePerMonth` to derive deeper insights, visualized with line and bar charts.
- **Visualization Enhancements**:
  - Used modern color palettes (e.g., `husl`, `viridis`, `Set2`) for aesthetic appeal.
  - Added annotations, leader lines, and grids to ensure clarity, addressing issues like overlapping labels.

## Key Outcomes
This EDA phase identified potential churn drivers, such as high charges with short tenure and lack of add-on services, laying the groundwork for predictive modeling or targeted retention strategies. The combination of rigorous data cleaning, diverse analytical methods, and refined visualizations provides a solid understanding of the dataset’s dynamics.
