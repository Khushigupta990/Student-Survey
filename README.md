📊 Student Survey Data Analysis Project
📌 Overview

This project analyzes student survey data using Python.
It performs data cleaning, visualization, and statistical analysis to generate insights about students' study habits, motivation, and preferences.

🚀 Features
Data cleaning and preprocessing using pandas
Visualization using matplotlib
Analysis of Nominal, Ordinal, and Ratio data
Statistical summary (Mean, Median, Mode, Standard Deviation, Correlation)
Interactive charts and dashboard
Automatic export of charts as images
🛠️ Technologies Used
Python
pandas
numpy
matplotlib
Google Colab
📂 Dataset

The dataset is a CSV file containing:

Learning method
Device used for study
Semester/year
Satisfaction level
Motivation level
Study hours
Number of subjects
▶️ How to Run the Project
🔹 Option 1: Google Colab (Recommended)
Open the notebook in Google Colab
Click Runtime → Run All
Upload your CSV file when prompted
View charts and download outputs
🔹 Option 2: Run Locally

Step 1: Install dependencies

pip install pandas numpy matplotlib

Step 2: Modify file input

Replace this:

from google.colab import files
uploaded = files.upload()

With this:

df_raw = pd.read_csv("your_file.csv")

Step 3: Run the script

python your_script.py
📊 Output

The project generates:

chart1_nominal.png → Learning method & device usage
chart2_ordinal.png → Semester, satisfaction, motivation
chart3_ratio.png → Study hours & subjects
chart4_dashboard.png → Complete dashboard
📈 Key Insights
Most students prefer reading textbooks/notes
Laptops are the most commonly used device
Average study time is around 2 hours per day
Satisfaction and motivation levels are moderate
📖 Concepts Covered
Nominal Data
Ordinal Data
Ratio Data
Data Cleaning
Data Visualization
Descriptive Statistics
📌 Conclusion

This project shows how Python can be used to clean, analyze, and visualize real-world data.
It helps in understanding student behavior through simple and effective analysis.
