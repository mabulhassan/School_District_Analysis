# School_District_Analysis
The spreadsheet ##new_full_student_data## is a flat file with student and school information for a specific district. The columns include math scores, reading scores, gradse, student ids, in addition to school information such as school type, budget and school name.

##Data Cleansing##
The data was cleansed by removing duplicates and null values from the spreadsheet prior to summarizing resuls. This was done using the library pandas which includes dataframe feature and properties such as dropna(), duplicated() and drop_duplicates(). 

##Data Analysis and Summary##
The same libraries were imported to perform data analysis. The results are displayed for several queries to filter data and summarize tables with school names, student reading scores and math scores. An oversview of statistical anlaysis of the data was generated to create the mean, mode, count, standard deviation, min, max, top and bottom 25% scores of students for each grade. 
Finally a summary of math scores by grade and school type are displayed. In addition, a summary table with a total count of all students by school name is created using pandas dataframes and filtering. The summarized data creates a more organized view that allows for better understanding of student scores and analysis of the trends that impact those scores.
