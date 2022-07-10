# LSE_DA_COVID_analysis
LSE DA Course 2 Assignment's Summary
Summary of the work I have been doing for the main assignment, the details can be found in the Word document.

Week 1:
I created a GitHub repository.

Week 2:
Import and assess the data types, columns, rows, and missing values.
I have created subsections to better handle the amount of data (see Gibraltar). I have filtered and displayed the data.
I have subset the Gibraltar DataFrame with relevant columns and run the describe() function.

Week 3:
I have merged the cov and vac DataFrames and wrangled the data.
I viewed and determined data types as well as columns and rows.
Converted the Date type to DateTime from object and dropped unnecessary columns.
To determine the number of cases across the UK, I have used the groupby() and aggregate() functions to calculate differences between the application of the first and second dose.
I then have determined: Which Province/State has the highest number of individuals who have received a first dose but not a second dose?
Which Province/State has the highest percentage of individuals who have received a first dose but not a second dose?
How has the number of vaccinated individuals and individuals who have received the first and second doses, changed over time?

Week 4:
I have added a column with the difference per region for the sum of first doses minus the sum of the second doses. Then, I calculated the ratioto obtain the number of individuals eligible for the second dose as a percentage.
I then plotted a vertical bar graph to display the percentage for the first dose to fully-dosed individuals while also adding distinct tick labels to the barplot to make it easier for the audience to read the plot.
I have saved this visualisation in an exported and shareable format (PNG).
I have grouped the data by Province/State and Date, and aggregated the death count to create a lineplot to display the trend of deaths across all regions over time.
I determined which Province/State causes the data set to be skewed and excluded it.
I converted Date into Months and plotted the same line graph as previously and saved this visualisation in an exported and shareable format (PNG).
I did the same for the recovered and created a lineplot which I then exported.

Week 5:
Imported, read, and printed the tweet dataframe.
Created a new df to determine the hashtags and the top trending hashtags.
Created a visualisaion.

Week 6:
Performed predictive analysis through time-series forecast, answered to the additional questions and proposed effective solutions to the stakeholder.
