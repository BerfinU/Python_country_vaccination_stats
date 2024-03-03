# Python_country_vaccination_stats

# Data Set Update and SQL Imputation

This Python script imputes data by reading data from a CSV file and then updating a table in a SQL Server database. Below is a step-by-step explanation:

1. Data Set Reading and Processing:
   - First, the dataset is read into a DataFrame using the pandas library and the necessary processing is done.
   - Missing values are filled according to the minimum number of daily vaccinations for each country.
   - If a country has no daily immunization data, these values are filled with zero.
   - The top 3 countries with the highest median daily vaccination numbers and the total number of vaccinations on a given date are calculated.

2. SQL Imputation:
   - Next, the information required to connect to SQL Server is specified and the connection is established.
   - The SQL query updates the missing values by calculating the median of the number of daily immunizations for each country.
   - This SQL query performs the imputation of the missing data by updating the corresponding table in the database.

3. Execution and Results:
   - When the Python script is run, the dataset is updated and the SQL query is successfully executed.
   - The results are printed on the screen and appropriate messages are shown in case of any errors.

Using this script, you can fill in missing data in a data set and update a table in SQL Server. It is a tool that can be used in data analytics and data management projects.
