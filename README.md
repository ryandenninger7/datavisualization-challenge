# datavisualization-challenge
Project Summary: Mouse Cancer Treatment Analysis

This project involves the analysis of mouse cancer treatment data using Python and data visualization libraries. The provided data includes information about various drug regimens administered to mice and their corresponding responses. The analysis covers data preparation, summary statistics, creation of bar and pie charts, identification of outliers, and correlation/regression analysis.

Data Preparation:
Run the provided package dependencies and import data.
Merge the mouse_metadata and study_results DataFrames.
Identify and remove duplicate mouse IDs with duplicate time points.
Display the number of unique mouse IDs before and after cleaning.

Generate Summary Statistics:
Create a DataFrame of summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.

Create Bar Charts and Pie Charts:
Generate two identical bar charts showing the total number of rows for each drug regimen using Pandas and Matplotlib.
Generate two identical pie charts displaying the distribution of female vs. male mice in the study using Pandas and Matplotlib.

Calculate Quartiles, Find Outliers, and Create a Box Plot:
Calculate the final tumor volume for mice in selected treatment regimens.
Determine outliers using quartiles and IQR.
Create a box plot to visualize the distribution of final tumor volume, highlighting potential outliers.

Create a Line Plot and a Scatter Plot:
Generate a line plot of tumor volume vs. time point for a single mouse treated with Capomulin.
Create a scatter plot of mouse weight vs. average observed tumor volume for the entire Capomulin regimen.

Calculate Correlation and Regression:
Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the Capomulin regimen.
Plot the linear regression model on top of the scatter plot.
By following these steps, the analysis provides a comprehensive understanding of the effects of different drug regimens on mice, emphasizing key trends, outliers, and correlations between variables.
