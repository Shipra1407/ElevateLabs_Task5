# ElevateLabs_Task5
 # Student Performance - Exploratory Data Analysis (EDA)
This project explores how factors like gender, lunch type, parental education, and test preparation impact students' performance in Math, Reading, and Writing.

# Dataset Info
File Name: StudentsPerformance.csv

Records: 1000 students

Columns: 8 (categorical + numerical)

Features include:

gender

race/ethnicity

parental level of education

lunch (standard / free-reduced)

test preparation course (completed / none)

math score, reading score, writing score

# Tools Used
Python 3 (Google Colab)

Pandas

Seaborn

Matplotlib

FPDF / MS Word (for report)

# EDA Workflow
✅ 1. Data Loading & Cleaning
Imported CSV using pandas.read_csv()

Cleaned column names

Checked for missing values & duplicates

✅ 2. Quick Dataset Overview
Used .head(), .info(), .describe()

Reviewed data types & basic stats

✅ 3. Univariate Analysis
Countplots for gender, lunch, etc.

Histograms and boxplots for score distributions

Detected outliers

✅ 4. Correlation & Pairwise Plots
Correlation heatmap (Math, Reading, Writing)

Pairplot for multivariate patterns

✅ 5. Bivariate Analysis
Average scores grouped by:

Gender

Race/Ethnicity

Test prep course

# Key Findings
📚 Reading & Writing scores are strongly correlated

👩 Female students do better in Reading & Writing

👨 Male students slightly ahead in Math

✅ Test prep boosts all scores noticeably

🍴 Standard lunch students perform better

🏅 Group E students score the highest overall

# Conclusion
This analysis shows how student demographics and preparation influence academic outcomes. The insights can help teachers create more personalized support and improve student success.

