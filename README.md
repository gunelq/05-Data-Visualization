# 05-Data-Visualization
Homework for Module 5-Data-Visualization
Wir this Homework we were able to work with Matplotlib. We generatied all of the tables and figures needed for the technical report of the clinical study

This assignment is broken down into the following tasks:

1.Prepare the data.

Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.Display the updated number of unique mice IDs.

2.Generate summary statistics.

Create a DataFrame of summary statistics. A summary statistics should include:
A row for each drug regimen. These regimen names should be contained in the index column.
A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

3.Create bar charts and pie charts.

Generate two bar charts. Both charts should be identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.Generate two pie charts. Both charts should be identical and show the distribution of female versus male mice in the study.

4.Calculate quartiles, find outliers, and create a box plot.

Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens. Use the following substeps:
Create a grouped DataFrame that shows the last (greatest) time point for each mouse. Merge this grouped DataFrame with the original cleaned DataFrame.
Create a list that holds the treatment names as well as a second, empty list to hold the tumor volume data.
Loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Append the resulting final tumor volumes for each drug to the empty list.
Determine outliers by using the upper and lower bounds, and then print the results.Using Matplotlib, generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlight any potential outliers in the plot by changing their color and style.


5.Create a line plot and a scatter plot.

Select a single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.
Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

6.Calculate correlation and regression.

Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
Plot the linear regression model on top of the previous scatter plot.



