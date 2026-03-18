🚗 Car Performance Analysis (EDA)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a car performance dataset to identify key factors that influence fuel efficiency and overall vehicle performance.

The analysis focuses on understanding relationships between variables such as horsepower, weight, engine size, and cylinders with miles per gallon (MPG).

🎯 Objectives

Clean and preprocess raw data

Perform exploratory data analysis

Identify trends and correlations

Visualize relationships between features

Derive meaningful business insights

📂 Dataset

File: car_performance.csv

Type: Structured dataset

Key Features:

MPG (Miles per Gallon)

Cylinders

Displacement

Horsepower

Weight

Acceleration

Model Year

Origin

🛠️ Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

🔍 Analysis Workflow
1. Data Understanding

Loaded dataset using Pandas

Reviewed structure, data types, and summary statistics

2. Data Cleaning

Handled missing values

Checked inconsistencies

Converted data types where necessary

3. Exploratory Data Analysis

Univariate analysis (distributions)

Bivariate analysis (relationships between variables)

Correlation analysis

4. Visualization

Histograms

Scatter plots

Bar charts

Correlation plots

📊 Key Insights

🚘 Heavier cars tend to have lower MPG (fuel efficiency)

⚙️ Higher horsepower is associated with reduced fuel efficiency

🔄 Larger engine displacement negatively impacts MPG

📉 Strong negative correlation between MPG and weight/displacement

📁 Project Structure
car-performance-analysis/
│
├── data/
│   └── car_performance.csv
│
├── notebooks/
│   └── car_performance_EDA.ipynb
│
├── README.md
▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/car-performance-analysis.git

Navigate to the folder:

cd car-performance-analysis

Install dependencies:

pip install pandas numpy matplotlib jupyter

Run the notebook:

jupyter notebook
