### What is the difference between Data Mining and Data Profiling?
- Data mining is the process of finding relevant info which hasn't been found before. It turns raw data into valuable info 
- Data profiling is done to assess a dataset for logic, uniqueness, and consistency. It can't identify incorrect or inaccurate values
### Define Data Wrangling in data analytics
- Data Wrangling is the process of cleaning, structuring and enrishing raw data into a usable format for better decision making
### What are common problems that data analysts encounter
- Handle duplicate and missing values
- Cellect meaning right data at the right time
- Handle data purging and storage problems
- Make data secure and deal with compliance issues
### Steps involved in any analytics project?
- Understand problem
- Collect data
- Data cleaning
- Data exploration/analysis
- Interpret results
### What tools have you used for analysis and presentation purposes?
- Microsoft Excel
- MySQL
- SQL
- Tableau
- Python
### Best practices for data cleaning?
- Make a data cleaning plan by understanding where the common erros take place and keep communications open
- Identify and remove duplicates before working with the data
- Focus on the accuracy of the data. Maintain the value types of data, provide mandatory constratins and set cross-field validation
- Standardize the data at the point of entry so that its less chaotic and you will be able to ensure that all info is standardized, leading to fewer errors on entry
### How can you handle missing values in a dataset?
- Listwise deletion - an entire record is exluded from analysis if a single value is missing
- Average imputation - use the average value of the responses from the other participants to fill in the missing value
- Regression substitution - use multiple-regression analysis to estimate a missing value
- Multiple imputation - creates plausible values based on the correlations for the missing data and then averages the simulated datasets by incorportaing random errors in your predictions
### What is a Normal Distribution?
- Normal Distribution will appear as a bell curve
- Median, Mean and Mode are all equal
- 68% of data falls within 1 SD of mean
- 95% of data falls within 2 SD of mean
- 99.7% of data falls within 3 SD of mean
### What is Time Series analysis?
- Statistical method that deals witih ordered sequence of values of a variable at equally spaced time intervals
### How is joining different from blending in Tableau?
- Data joining can be done when data comes from the same source
- All combined tables or sheets contain common set of Dimensions and Measures
- 2 tables from same database or 2 or more worksheets from same Excel file
- Data blending is used when data is from 2 or more different sources
- Each data source contains its own set of Dimensions and Measures in Data blending
- Combine Oracle table with SQL server or 2 sheets from Excel or combining Excel sheet and Oracle table
### How is overfitting different from underfitting?
- Overfitting model trains data too well using training set
- Performance drops significantly over test set
- Overfitting happens when model leanrs the noice and random fluctuations in training dataset in detal
- Underfitting doesn't train data well nor can it generatlize to new data
- Performs poorly on training and test set
- Underfitting happens when there is less data to build an accurate model and also when we try to build a linear model w/ a non-linear data
### Correct syntax for reshape() function in NumPy
- reshape(array,shape)
### What the difference between COUNT, COUNTA, COUNTBLANK, and COUNTIF in Excel?
- COUNT returns a count of number cells in a range
- COUNTA returns count of non-blank cells in a range
- COUNTBLANK returns count of blank cells in a range
- COUNTIF returns count of value by checking a given condition
### Explain how VLOOKUP works in Excel
- VLOOKUP is used when you need to find things in a table or range by row
### How do you subset or filter data in SQL?
- Use WHERE and HAVING clause
### What is the difference between WHERE and HAVING clause in SQL?
- WHERE clause works on row data
- WHERE clause filter occurs before any groupings are made
- Aggregate function can't be used - WHERE
- HAVING clause works on aggregated data
- HAVING is used to filter values from a group
- Aggregate functions can be used - HAVING
### What are the different ways to create a dataframe in Pandas?
- By initializing a list
- By initializing a dictionary
### Write the Python code to create an employees dataframe from teh "emp.csv" file and display the head and summary of it
`import pandas as pd`  
`df = pd.read_csv('emp.csv')`  
`df.head()`  
`df.describe()`
### How will you select the Department and Age columns from an Employees dataframe in Python?
`Employees[['Department','Age']]`  
### What is the criteria to say whether a developed data model is good or not?
- A good model should be intuitive, insightful, and self-explanatory
- The model developed should be able to be easily consumed by the clients for actionable and profitable results
- A good model should easily adapt to changes according to  business requirements
- If the data gets updated, the model chould be able to scale according to new data
### What is the significance of Exploratory data analysis (EDA)?
- EDA helps to understand the data better
- Helps you obtain confidence in data to a point where you're ready to engage a ML algorithm
- It allows you to refind your selection of feature variables that will be used later for model building
- Can discover hidden trends and insights from data
### How do you treat outliers in a dataset?
- Drop outliers
- Cap your outliers data
- Assign a new value
- Try a new transformation
### Explain descriptive, predictive, and prescriptive analytics
- Descriptive provides insights into the past to answer "what has happened"
- Descriptive uses data aggregation and data mining techniques
- Predictive understands the future to answer "what could happen"
- Predictive uses statistical models and forecasting techniques
- Prescriptive suggests various courses of action to answer "what should you do"
- Prescriptive uses optimization and simulation algorithms to advise possible outcomes
### What are the different types of sampling techniques used by data analysts?
- Sampling is a statistical method to select a subset of data from an entire dataset(population) to estimate the characteristics of the whole population
- Simple random sampling
- Systematic sampling
- Cluster sampling
- Stratified sampling
- Judgmental or purposive sampling
### What are the different types of Hypothesis testing?
- Null hypothesis states there is no relation betweeen the predictor and outcome variables in the population
- Alternative hypothesis states there is come relation between the predictor and outcome variables in the population
### Describe univariate, bivariate, and multivariate analysis
- Univariate analysis is the simplest form of data analysis where the data being analysed contains only 1 variable
- Univariate analysis can be described using: Central Tendency, Dispersion, Quartiles, Bar charts, Histograms, Pie charts, Frequency distribution tables
- Bivariate analysis involves analysis of 2 variables to find causes, relationships, and correlations between the variables
- Bivariate analysis can be explained using: Correlation coefficients, Linear regression, Logistic regression, Scatter plots, Box plots
- Multivariate analysis involves analysis of 3 or more variables to understand the relationship of each variable with the other variables
- Multivariate analysis can be performed using: Multiple regression, Factor analysis, Classification & regression trees, Cluster analysis, Principal component analysis, Clustering bar chart, Dual axis charts
### What function whould you use the get current date and time in Excel?
- You can use the TODAY() and NOW() function to get the current date and time
### In SQL, can you use alias in WHERE clause?
- You can't use an alias while filtering data using the WHERE clause
### How are UNION, INTERSECT, and EXCEPT used in SQL?
- UNION is used to combine the results of 2 or more SELECT statements
- INTERSECT returns the common records that are the results of 2 or more SELECT statements
- EXCEPT returns the uncommon records that are the results of 2 or more SELECT statements
### What is the difference between Treemaps and Heatmaps in Tableau?
- Treemaps are used to display data in nested rectangles
- You use dimensions to define the structure of the treemap, and measures to define the size or color of the individual rectangles
- Treemaps are a relatively simple data viz that can provide insight in a visually attractive format
- Heatmap helps visualize measures against dimensions with the help of colors and size to compare 1 or more dimensions & up to 2 measures
- The layout is similar to a text table w/ variations in values encoded as colors
- In heatmap, you can quickly see a wide array of info
### Why are pivot tables used?
- Pivot tables are used in Excel to summarize, analyze, and present large amounts of data in a quick and easy-to-understand format. 
- Summarizing large amounts of data: Pivot tables allow you to summarize large amounts of data quickly and easily, by grouping data by categories or fields of your choice.
- Analyzing data: Pivot tables allow you to analyze data in multiple dimensions, making it easy to spot trends, patterns, and outliers in your data.
- Flexible reporting: Pivot tables offer a high degree of flexibility, allowing you to quickly change the layout and presentation of your data. This makes it easy to create custom reports that meet your specific needs.
- Easy customization: Pivot tables are highly customizable, allowing you to choose the fields you want to include, and how you want to group and summarize your data.
- Time-saving: Pivot tables can save a lot of time compared to manually analyzing data. Once you have created a pivot table, you can update it with new data in a matter of seconds, and the table will automatically update itself to reflect the changes.
 -Overall, pivot tables are a powerful tool for anyone who needs to work with large amounts of data in Excel. They provide a quick and easy way to summarize and analyze data, and can save a lot of time and effort compared to manual analysis.
### How to create a pivot table in Excel
- To create a pivot table in Excel, follow these steps:
- Select the data that you want to use in your pivot table. This data should be organized in a tabular format with column headers.
- Click on the "Insert" tab in the Excel ribbon.
- Click on the "PivotTable" button in the "Tables" group.
- In the "Create PivotTable" dialog box that appears, make sure that the correct range of data is selected.
- Choose where you want to place the pivot table. You can either create a new worksheet or place the table in an existing one.
- Click on the "OK" button.
- The PivotTable Field List pane will appear on the right side of the screen. In this pane, you can select the fields you want to include in your pivot table.
- Drag the fields you want to include in the "Rows" and "Values" areas of the field list.
- If you want to summarize your data by a particular field, drag that field to the "Columns" area.
- You can also apply filters to your pivot table by dragging a field to the "Filters" area
- Once you have arranged the fields to your liking, you can customize the pivot table further by using the various options in the "Design" tab in the Excel ribbon.
- When you are finished, you can save and print your pivot table as you would any other Excel worksheet.
