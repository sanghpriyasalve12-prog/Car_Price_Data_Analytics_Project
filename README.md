# Car_Price_Data_Analytics_Project
Data analytics project focused on cleaning and exploring a car pricing dataset using Python. Includes data loading, preprocessing, handling missing values, removing outliers, and EDA to uncover patterns between vehicle features and price, producing a structured dataset ready for further modeling and insights.
Car Price Data Analytics Project
# Overview
This project focuses on data cleaning and exploratory data analysis (EDA) of a car pricing dataset using Python in Jupyter Notebook.
The goal is to transform raw data into a structured, analysis-ready format and uncover patterns that influence vehicle pricing.
This project demonstrates practical skills in:
- Data preprocessing
- Data quality checks
- Exploratory data analysis
- Insight extraction
# Dataset
The dataset contains information about cars and their specifications.
Main features include:
- Make & Model
- Year
- Horsepower (HP)
- Cylinders
- Transmission Type
- Driven Wheels
- Number of Doors
- Vehicle Size
- Highway MPG & City MPG
- Popularity
- Price (Target Variable)
The dataset was cleaned to remove duplicates, handle missing values, and standardize column names.

# Tools & Technologies
- Python
- Jupyter Notebook
- Pandas – data manipulation
- NumPy – numerical operations
- Matplotlib & Seaborn – data visualization
  
# Project Steps
1. Data Loading
- Imported dataset into Jupyter Notebook
- Inspected structure, shape, and data types
2. Data Cleaning
- Removed unnecessary columns
- Renamed columns for consistency
- Checked and handled missing values
- Removed duplicate records
- Performed outlier detection using IQR method
3. Exploratory Data Analysis (EDA)
- Analyzed distributions of key numerical features
- Studied relationship between Price and Horsepower
- Compared fuel efficiency vs price
- Used boxplots, histograms, and scatterplots for insights
4. Data Preparation Outcome
- Produced a cleaned dataset ready for modeling or advanced analysis
  
# Dashboard / Visual Outputs
- Key visualizations created during analysis:
- Price distribution histogram
- Horsepower vs Price scatter plot
- Boxplots for detecting outliers
- MPG comparisons
- (Visuals can be viewed directly in the notebook.)

# Results & Insights
- Vehicle price shows a positive relationship with horsepower
- Price distribution is right-skewed, with fewer luxury outliers
- Data cleaning significantly improved reliability of analysis
- Removing outliers provided a more realistic view of market trends


How to Run the Project
Clone the repository
git clone <repository-link>
cd car-price-analysis
Install required libraries
pip install -r requirements.txt
Launch Jupyter Notebook
jupyter notebook
Open the notebook file and run all cells.
Project Structure
car-price-analysis/
│
├── data/
│   └── car_price_clean_data.csv
│
├── notebooks/
│   └── car_price_data-analysis.ipynb
│
├── outputs/
│   └── figures/
│
├── README.md
└── requirements.txt
