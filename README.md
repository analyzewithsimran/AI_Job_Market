📌 Project Overview

This project analyzes the AI Job Market using real-world structured data.
The goal is to explore hiring trends, salary ranges, demand for technical skills, industry growth, and experience-level requirements.

Using Pandas, NumPy, Matplotlib, and Seaborn, I performed data cleaning, transformation, exploratory data analysis (EDA), and data visualization to extract valuable insights from the dataset.

🎯 Objectives of the Project

Understand the hiring trends in the AI/ML domain
Analyze salary ranges and identify high-paying industries
Explore which skills & tools are most in-demand
Visualize patterns across industries, experience levels, and job dates
Practice Python, Pandas, NumPy, and visualization libraries in a real dataset

🧹 Data Cleaning & Preprocessing Steps

Loaded the dataset using Pandas
Converted salary ranges into numeric min_salary and max_salary
Created a new salary_score (average salary indicator)
Converted posted_date into datetime format
Split skills_required into individual skills using explode()
Handled missing values and standardized text columns

📊 Key Insights from the Analysis
🔹 1. Industry Demand

Identified which industries hire the most AI professionals and which offer the highest salaries.
🔹 2. Skills & Tools Popularity

Visualized the top technical skills (like Python, PyTorch, SQL, Scikit-learn, etc.)
and tools preferred across roles.
🔹 3. Salary Trends

Highest paying job roles
Average salaries across industries

Salary distribution using histograms
🔹 4. Experience Level Comparison

Compared Entry, Mid, and Senior roles using bar charts and violin plots.
🔹 5. Time-Series Trends

Visualized job posting trends month-by-month to understand hiring cycles.

📈 Visualizations Included

This project contains multiple charts built using Matplotlib & Seaborn:
Bar chart: Job postings per industry
Pie chart: Experience level distribution
Histogram: Salary score distribution 
Line chart: Monthly job posting trends
Boxplot: Salary vs Industry
Scatterplot: Minimum vs Maximum salary
Heatmap: Salary correlation matrix
Top Skills Frequency Chart
These charts help build a strong understanding of the job market landscape.

🧠 Skills Used in This Project
Python Programming

Pandas (data cleaning, transformation, EDA)
NumPy (numerical operations, arrays, statistical calculations)
Matplotlib (static visualizations)
Seaborn (statistical visualizations)
Data Wrangling
Exploratory Data Analysis
Data Visualization & Interpretation

📂 Notebook Structure
01 — Importing Libraries  
02 — Loading the Dataset  
03 — Data Cleaning  
04 — Feature Engineering (salary_score, exploded skills, etc.)  
05 — Exploratory Data Analysis  
06 — Visualizations  
07 — Insights & Conclusions  

🧾 Conclusion

This project provides a complete analysis of the AI job market and helps identify:
Which industries hire the most
What skills are in demand
Which roles offer high salaries
How hiring trends fluctuate over time
It demonstrates my ability to work with real datasets, perform data cleaning, run EDA, and create meaningful visualizations — essential skills for Data Analyst and Data Science roles.
🚀 Future Improvements
Build a job recommendation system (based on text similarity)
Build an ML model to predict salary ranges
Create an interactive dashboard using Power BI or Plotly
