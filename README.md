📊 Student Survey Data Analysis Project
📌 Overview

This project analyzes student survey data using Python. It performs data cleaning, visualization, and statistical analysis to generate meaningful insights about students' study habits, motivation, and preferences.

🚀 Features
✅ Data cleaning and preprocessing using pandas
📊 Visualization using matplotlib
📈 Analysis of:
Nominal data (categories)
Ordinal data (rankings)
Ratio data (numerical values)
📉 Statistical summary:
Mean, Median, Mode
Standard Deviation
Correlation
📋 Interactive charts and dashboard
📥 Automatic export of charts as images
🛠️ Technologies Used
Python 🐍
pandas
numpy
matplotlib
Google Colab (for execution)
📂 Dataset

The dataset is a CSV file containing student responses such as:

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
Click Runtime → Run all
Upload your CSV file when prompted
View charts and download outputs
🔹 Option 2: Run Locally
Step 1: Install dependencies
pip install pandas numpy matplotlib
Step 2: Modify file input

Replace:

from google.colab import files
uploaded = files.upload()

With:

df_raw = pd.read_csv("your_file.csv")
Step 3: Run the script
python your_script.py
📊 Output

The project generates:

📈 chart1_nominal.png → Learning method & device usage
📊 chart2_ordinal.png → Semester, satisfaction, motivation
📉 chart3_ratio.png → Study hours & subjects
🧾 chart4_dashboard.png → Complete dashboard
📌 Key Insights (Example)
Most students prefer reading textbooks/notes
Majority use laptops for studying
Average study time ≈ 2 hours/day
Moderate satisfaction and motivation levels
📖 Concepts Covered
Data Types:
Nominal
Ordinal
Ratio
Data Cleaning
Data Visualization
Descriptive Statistics
🤝 Contribution

Feel free to fork this repository and improve the analysis or add new visualizations!

📜 License

This project is for educational purposes.
