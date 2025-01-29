## Data Science Workflow: "If I Study More, Will I Get a Higher Grade?"

### Overview

This project explores a fundamental data science workflow using the question: "If I study more, will I get a higher grade?" The workflow involves data cleaning, exploratory data analysis (EDA), applying machine learning techniques, and deriving insights from the data.

### Steps Followed

### Data Cleaning

Manually cleaned the initial dataset by addressing missing values and correcting invalid entries.

Shared the dataset with a peer who performed additional cleaning, ensuring consistent and valid data.

### Data Augmentation

Added new rows to simulate additional scenarios and increase the dataset size.

### Exploratory Data Analysis (EDA)

Visualized the data using scatter plots and box plots to understand the relationship between hours studied and grades.

Observed the data distribution and identified trends and potential outliers.

### Key Observations from EDA

A positive correlation exists between hours studied and grades, indicating that studying more generally leads to higher grades.

Outliers were identified, such as unrealistic grades exceeding 100.

### Applying Machine Learning

Implemented a linear regression model to encode the observed relationship between hours studied and grades.

Derived a mathematical equation for the relationship: y=mx+c

Where  is the slope (rate of grade improvement per hour studied) and  is the intercept.

### Visualization of the Relationship

Highlighted abnormal data points (outliers) using boxpot

### Outlier Analysis

Used statistical methods (IQR) to detect and analyze outliers.

Addressed outliers by either capping them within valid ranges or removing them, depending on their nature.

### Technologies Used

### Programming Language: Python

### Libraries:

NumPy: For numerical computations.

Pandas: For data cleaning and manipulation.

Matplotlib: For data visualization.

Seaborn: For enhanced visualizations.

Scikit-learn: For machine learning (linear regression).

### Observations and Insights

1. Studying more hours is generally associated with higher grades.
2. After a point,the grade becomes saturated and is not affected by no of hours studied to that extent.
3. Outliers can significantly affect the relationship and need to be addressed during analysis.

