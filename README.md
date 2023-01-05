# IBM Data Science Capstone Project

# About
This is the capstone project to the Coursera IBM Data Science Professional Certificate. It encompasses everything learned in the course including Data Analysis Methodologies, Data Collection, Data Wrangling, Dash, Visualization, SQL, Python, Statistical Analysis, and Machine Learning

# Data Analysis Methodologies 
  - What ist he problem you are trying to solve?
  - How can you use data to answer the questions 
  - What data do you need to answer the questions?
  - Where is data coming from and how will you get it?
  - Is the data collection representative of the problem to be solved?
  - What additional work is required to manipulate and work with the data?
  - In what way can the data be visualzied to get the answer that is required?
  - Does the model used really answer the original question?
  - Can you put the model into practice?
  - Can you get constructive feedback into answering the question?
# Data Collection 
  - Collection through rest API's
  - Webscrapping 
    - Beautiful Soup
# Data Wrangling 
  - PreProcessing: converting raw data into a managable format for further analysis
  - Drop missing values with df.dropna()
    - axis = 0 drops the entire row
    - axis = 1 drops entire column 
  - Replace missing values with df['Column Name'].replace(np.nan, new_value)
# Data Analysis 
  - Formatting 
    - Normalization 
      - Simple Featuring Scaling 
        - df['Col-a']= df['Col-a']/df['Col-a'].max()
        - Xnew = (Xold/Xmax)
      - min-max
        - df['A']=(df['A']-df['A'].min())/ (df['A'].max()-df['A'].min())
        - Xnew = (Xold - Xmin)/(Xmax-Xmin)
      - z-score
        - df['A']=(df['A']-df['A'].mean())/(df['A'].std())
        - Xnew = (Xold-mean)/Std
     - Binning 
     - 
# Visualizations 
  - Seaborn
    - Lineplot
    - Barplot
    - Scatterplot 
    - Pointplot 
    - Countplot
    - Boxplot
  - Matplotlib
    - Lineplot
    - Barplot
    - Scatterplot
    - Pie Chart
    - Histogram
    - Boxplot
  - Dash on plotly
# SQL
  - Select Statements
    - DISTINCT
    - * 
    - MIN
    - MAX
  - From Statements 
    - Table name, dedicates where the information will be taken from 
  - Where Conditions 
    - LIKE '%%' 
    - Column_Name = ''
  - View Statements
    - CREATE VIEW view_name AS SELECT column1 FROM table_name WHERE ... 
    - REPLACE VIEW 
    - DROP VIEW view_name  
  - Join Statements 
     - Inner Join 
      - Selects the rows that satisfy the join conditions on both tables 
        - SELECT columns_1 FROM table_1 INNER JOIN table_2 
     - Full Outer Join
      - Joins all rows from both tables 
     - Left Outer Join 
      - Joins all rows from the left table and only the matching rows from the right table 
     - Right Outer Join 
      - Joins all rows from the right table and only the matching rows from the left table 
  - Stored Procedures 
    - 
  - Transactions
    - 
# Statistical Analysis
# Machine Learning 
  - K Nearest Neighbor (KNN): is a supervised learning algorithm used for classification and regression. The goal is to predict the label of a data point based on the points nearest to it. 
  - Decision Tree: 
