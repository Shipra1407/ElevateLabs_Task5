# ElevateLabs_Task5
# Exploratory Data Analysis (EDA) – Student Performance Dataset
This project presents a detailed exploratory analysis of the StudentsPerformance.csv dataset.
The goal is to uncover insights into how different factors such as gender, parental education, lunch type, and test preparation affect students' academic performance in Math, Reading, and Writing.

# About the Dataset
File Name: StudentsPerformance.csv
Records: 1000 students
Features: 8 columns
Data Types: Categorical + Numerical
# Features Included:
gender
race/ethnicity
parental level of education
lunch (standard or free/reduced)
test preparation course (completed or not)
math score
reading score
writing score
# Tools & Libraries Used
Python 3 (Google Colab)
Pandas
Seaborn
Matplotlib
FPDF / MS Word (for report generation)
# EDA Steps Followed
✅ Step 1: Data Loading & Cleaning
Loaded the dataset using pandas.read_csv()
Cleaned column names for consistency
Checked for missing values and duplicates
✅ Step 2: Dataset Overview
Viewed top records using .head()
Inspected data types using .info()
Generated summary statistics with .describe()
✅ Step 3: Univariate Analysis
Countplots for categorical columns like gender, lunch, etc.
Histograms and boxplots for scores
Outlier and distribution detection
✅ Step 4: Correlation & Pairplot
Correlation heatmap to identify relationships
Pairplot to explore multivariate score patterns
✅ Step 5: Bivariate Analysis
Grouped average scores by:
Gender
Race/Ethnicity
Test Preparation Course
# Key Insights
🧠 Reading & Writing scores are highly correlated
👩‍🎓 Female students score higher in Reading and Writing
👨‍🎓 Male students slightly outperform in Math
📚 Students who completed test prep scored significantly higher
🍽️ Students with standard lunch performed better
🏅 Group E students had the best overall performance

# Conclusion
This EDA highlights the impact of demographics and preparation on academic performance.
The findings can help educators design targeted academic interventions and provide data-driven support to students.
