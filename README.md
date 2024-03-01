# Global Retail Bank Customer Analysis

This project presents an analysis of a global retail bank's customer data. The data is sourced from [Kaggle](https://www.kaggle.com/datasets/charlottetu/customer-base-global-retail-bank/data).

## Data Exploration

The analysis begins with a basic exploration of the data. This includes checking the structure of the data, summarizing the data, and checking for missing values. The distribution of the data is also visualized using histograms for numerical columns and pie charts for categorical columns.

## Data Cleaning

The data is then cleaned by removing outliers from the numerical columns. This is done using the Z-score method, where values with a Z-score greater than 3 are considered outliers and are removed.

## Data Analysis

The cleaned data is then analyzed. The correlation between numerical variables is calculated and visualized using a heatmap. 

The relationships between 'Market' and 'Revenue', 'Market' and 'TRB', and 'TRB' and 'Revenue' are explored using box plots. For the relationship between 'TRB' and 'Revenue', the 'TRB' values are binned and the data is grouped based on these bins before plotting.

The relationships between 'Insurance', 'Investment', 'Mortgage' (and all of these products) and 'Revenue' are also explored. The data is reshaped and merged, and the relationships are visualized using a box plot.

## Conclusion

Through this analysis, we gain valuable insights into the characteristics of the global retail bank's customers and how these characteristics relate to revenue. This information can help the bank better understand their customers and develop more effective business strategies.

## Code

All the analysis code can be found in this [GitHub](https://github.com/asuraxo/Global_Retail_Bank_Customer_Analysis.git) repository.# Global_Retail_B;2Dank_Customer_Analysis
