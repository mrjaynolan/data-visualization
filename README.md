# Tumor Volume Analysis for Mouse Treatment Regimens

This Jupyter Notebook analyzes the effects of different drug regimens on tumor volume in mice. The analysis includes data preparation, summary statistics, visualizations, and statistical analysis.

## Main Categories

### 1. Prepare the Data
* Merging Datasets: The Mouse_metadata.csv and Study_results.csv datasets are merged into a single DataFrame on the Mouse ID column.
* Number of Mice: The total number of unique mice in the merged DataFrame is calculated.
* Finding Duplicate Mice: Duplicate entries are identified based on Mouse ID and Timepoint.
* Creating Clean DataFrame: A clean DataFrame is created by removing duplicate entries.
* Number of Mice in Clean DataFrame: The total number of unique mice in the clean DataFrame is recalculated.

### 2. Generate Summary Statistics
![Summary_Statistics_SS1](https://github.com/user-attachments/assets/1cacdca5-fe5a-4c67-bba5-bd9448f18c24)

![Summary_Statistics_SS2](https://github.com/user-attachments/assets/f5e55619-9be1-4e7b-9fbc-8a703a449340)

### 3. Create Bar Charts and Pie Charts



### 4. Calculate Quartiles, Find Outlirs, and crate a Box Plot

### 5. Creat a Line Plot and a Scatter Plot

### 6. Calculate Correlations and Regression


## Final Analysis

### Data Preperation

The datasets were successfully merged to form a comprehensive dataset containing both metadata and study results. Duplicate entries were identified and removed, ensuring data integrity for subsequent analysis.

### Summary Statistics

Summary statistics revealed significant differences in tumor volumes across different drug regimens. Capomulin and Ramicane showed the lowest mean tumor volumes, suggesting their effectiveness in reducing tumor size.

### Visualizations

Bar charts and pie charts provided a clear visual representation of the data distribution and gender distribution among the mice. The box plot highlighted the variability and potential outliers in the tumor volume data for each treatment regimen.

### Tumor Volume Trends

The line plot for a single mouse treated with Capomulin demonstrated a decreasing trend in tumor volume over time, indicating the effectiveness of the treatment.

### Weight and Tumor Volume Correlation

The scatter plot showed a positive correlation between mouse weight and average tumor volume in the Capomulin regimen. The linear regression model further confirmed this relationship, suggesting that heavier mice tend to have larger tumors.

### Conclusion

The analysis provides valuable insights into the effectiveness of different drug regimens in reducing tumor volume in mice. Capomulin and Ramicane were the most effective treatments, as evidenced by lower average tumor volumes. The correlation between weight and tumor volume highlights the importance of considering weight as a factor in treatment efficacy.

This comprehensive analysis demonstrates the power of statistical methods and visualizations in understanding and communicating the results of medical studies. The findings can guide future research and treatment strategies for reducing tumor size in mice.




