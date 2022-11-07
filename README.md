# Data-Cleaning-and-visualization using Pandas
### Objective: Analyze the Sales data and help to make decision on how to grow business
- Problem Statements:
  - What was the best month for Sales and what was the amount earned on those months ?
  - Which city had highest number of Sales ?
  - What time should the company put the advertisements so as to increase the likelihood of Sales ? 
- Steps Followed:
    - Firstly import Pandas library and read all the source files 
    - Merge all month's data into single dataframe.
    - Check for errors such as NaN,Null or blank rows
    - I have used isna(),isnull() to check the errors and have removed them using pd.dropna()
    - Then I have analyzed the problem.
    - I had to add few columns and do some calculations to solve the issue of total Sales
    - Looked for the data type of records while performing statistical calculations
    - Found that Order Date was not given in Date time format, so had to convert to same . I have used pd.to_datetime()
    - After solving each problem, I have visualized them in Bar Chart using Python's Matplotlib library !
    
