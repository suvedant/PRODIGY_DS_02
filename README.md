# PRODIGY_DS_02
Load the Data

Import necessary libraries (pandas, numpy, matplotlib, seaborn).
Read the dataset (train.csv).
Check for Missing Values

Identify columns with missing values.
Fill missing values (Age with median, Embarked with mode).
Drop the Cabin column due to too many missing values.
Data Exploration

Check dataset statistics (.info(), .describe()).
Count unique values in categorical columns.
Visualize Data

Plot survival distribution.
Analyze survival by gender, class, and age using bar charts and histograms.
Find Relationships

Use correlation heatmap (sns.heatmap()).
Check how "Pclass", "Fare", and "Sex" influence survival.
Conclusion

First-class and female passengers had higher survival rates.
Higher fares were linked to better survival chances
