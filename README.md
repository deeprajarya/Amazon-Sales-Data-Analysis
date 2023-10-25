# Amazon Sales Data Analysis

## Introduction
This README file provides an overview of the Amazon Sales Data Analysis project. The purpose of this analysis is to gain insights into sales trends, profitability, and other key metrics using the "Amazon_Sales_Records.csv" dataset.

## Dataset
The dataset used for this analysis contains sales records from Amazon. It includes the following columns:

- Region
- Country
- Item Type
- Sales Channel
- Order Priority
- Order Date
- Order ID
- Ship Date
- Units Sold
- Unit Price
- Unit Cost
- Total Revenue
- Total Cost
- Total Profit

This project will involve data preprocessing, exploratory data analysis, feature engineering and data visualizaton.
## Analysis Process

### Data Preprocessing
- Loaded the dataset using Pandas.
- Converted date columns to datetime format.
- Checked for missing values.

### Exploratory Data Analysis (EDA)
- Explored the data through various visualizations:
  - Year-wise, month-wise, and day-wise sales trends.
  - Grouped data by item type and sales channel.
  - Examined data distributions and potential outliers.
  - Calculated summary statistics.

### Feature Engineering
- Created new features:
  - Order Year, Month, Quarter, and Day.
  - Calculated Profit Margin (%), Sales Growth Rate (%), and Cost-to-Revenue Ratio (%).

### Data Visualization
- Visualized insights using:
  - Line plots for sales trends.
  - Boxplots to analyze profit margins.
  - Pairplots for feature relationships.
  - Barplots for annual performance.

### Conclusion
- Summarized key findings and insights from the analysis.
- Provided recommendations based on the insights.
- Mentioned potential directions for future work, such as building predictive models or in-depth analyses.

## Usage
- The code for this analysis can be found in the accompanying Jupyter Notebook (or Python script).
- The cleaned dataset is saved as "sales_data_cleaned.csv."
- Use the code and visualizations to explore the data and gain further insights.

## Dependencies
- This analysis was conducted using Python, and the following libraries were used:
  - Pandas
  - Numpy
  - Matplotlib
  - Seaborn

## Contributors
- [Deepraj Arya]


## License
This project is licensed.

## Feedback
- If you have any valuable feedback, feel free to contact at https://www.linkedin.com/in/deepraj-arya-3060631b7
