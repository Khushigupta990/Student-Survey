
📊 Student Survey Data Analysis Project

📌 Overview

This project analyzes student survey data using Python.
It includes data cleaning, visualization, and statistical analysis to generate meaningful insights about students' study habits, motivation, and preferences.


---

🚀 Features

Data cleaning and preprocessing using pandas

Data visualization using matplotlib

Analysis of:

Nominal Data

Ordinal Data

Ratio Data


Statistical summary:

Mean

Median

Mode

Standard Deviation

Correlation


Interactive charts and dashboard

Automatic export of charts as images



---

🛠️ Technologies Used

Python

pandas

numpy

matplotlib

Google Colab



---

📂 Dataset

The dataset is a CSV file containing the following fields:

Learning method

Device used for study

Semester / Year

Satisfaction level

Motivation level

Study hours

Number of subjects



---

▶️ How to Run the Project

🔹 Option 1: Google Colab (Recommended)

# Step 1: Open notebook in Google Colab
# Step 2: Run all cells

# Upload file
from google.colab import files
uploaded = files.upload()

# Continue execution to see results

Steps:

1. Open the notebook in Google Colab


2. Click Runtime → Run All


3. Upload your CSV file when prompted


4. View charts and download outputs




---

🔹 Option 2: Run Locally

✅ Step 1: Install Dependencies

pip install pandas numpy matplotlib

✅ Step 2: Modify File Input

Replace this:

from google.colab import files
uploaded = files.upload()

With this:

import pandas as pd

# Load dataset from local system
df_raw = pd.read_csv("your_file.csv")

✅ Step 3: Run the Script

python your_script.py


---

📊 Output

The project generates the following output files:

chart1_nominal.png → Learning method & device usage

chart2_ordinal.png → Semester, satisfaction, motivation

chart3_ratio.png → Study hours & subjects

chart4_dashboard.png → Complete dashboard



---

📈 Key Insights

Most students prefer reading textbooks/notes

Laptops are the most commonly used device

Average study time is around 2 hours per day

Satisfaction and motivation levels are moderate



---

📖 Concepts Covered

Nominal Data

Ordinal Data

Ratio Data

Data Cleaning

Data Visualization

Descriptive Statistics



---

📌 Conclusion

This project demonstrates how Python can be used to:

Clean real-world data

Perform statistical analysis

Create meaningful visualizations


It helps in understanding student behavior through simple and effective data analysis.

