# PGP_AIML
Learnings and projects done as part of Post Graduate Program in AI and ML from Simplilearn

This project is about performing Feature Engineering concepts on Housing Data. 

The various operations done are as follows

Course-End Project: Feature Engineering
Maria Nevis Danton Jesuraja A
PGP Data Science – Purdue University
Applied Data Science with Python
Source Code Jupyter Notebook structure:
• Importing Necessary Libraries
• Understand the dataset
• Separating categorical and numerical data
• EDA of Numerical Variables
• Removing columns that have more than 75% NULL/NaN values
• Dropping columns where 0 value count is more than 90%
• Filling missing values with mean()
• DisPlot for all numerical variables to visualize skewness
• Histogram for numerical_data
• Histogram for all numerical variables to visualize distributions
• Pair Plot of distribution and density, plotted for four columns at a time because it was taking too long to plot for the whole dataset at once
• Correlation matrix for numerical_data to check for significant variables
• Heatmap for the above correlation matrix
• EDA of categorical variables
• Removing columns that have more than 75% NULL/NaN values
• Removing observations containing Null/NaN any values
• Replacing NULL/NaN values with mode of their respective columns, if NULL/NaN value %age <= 20 in that column, filling the rest with 0 as the missing value percentage is more than 20%, so thought filling with a constant makes more sense
• CountPlot for all categorical variables
• BoxPlot for all categorical variables against SalePrice (Output Variable)
• Hypothesis Testing - Dropping categorical columns having p-value >= 0.05 against SalePrice(Output Variable)
• Combining all the significant num. and cat. Variables
• Outlier treatment for numerical features using Inter-Quartile Range (IQR)
• Visualization 9: BoxPlot for all significant variables
