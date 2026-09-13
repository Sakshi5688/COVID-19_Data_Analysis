COVID-19 Global Data Analysis

An end-to-end data analytics project using Python to analyze global COVID-19 trends, including cases, deaths, testing, vaccination, and population-based metrics.

📌 Project Overview

This project analyzes COVID-19 data across countries and continents to identify major trends and patterns. The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), statistical relationships, and visualizations.

🛠️ Technologies Used
Python
Pandas – Data cleaning and manipulation
NumPy – Numerical calculations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Jupyter Notebook
📂 Dataset

The project uses the Our World in Data (OWID) COVID-19 dataset, containing country-level information about:

COVID-19 cases
COVID-19 deaths
Testing
Vaccination
Population
Population density
Age demographics
GDP per capita
Hospital capacity
Life expectancy
🧹 Data Cleaning

The following preprocessing steps were performed:

Selected relevant columns for analysis
Removed aggregate/non-country records
Converted date values into proper datetime format
Checked missing values
Checked duplicate records
Validated population values
Identified and handled negative daily reporting values
Sorted data by country and date
📊 Feature Engineering

Created additional analytical metrics:

Death Rate (%)
Vaccination Rate (%)
Cases per 100,000 population
Deaths per 100,000 population

These features helped make meaningful comparisons between countries with different population sizes.

📈 Analysis Performed
Global COVID-19 Trends

Analyzed daily new cases and deaths to understand how the pandemic evolved over time.

Country-wise Analysis

Compared countries based on:

Total cases
Total deaths
Death rate
Cases per 100,000 population
Deaths per 100,000 population
Vaccination rate
Vaccination Analysis

Analyzed fully vaccinated populations and compared vaccination rates across countries.

Continent-level Analysis

Compared continents based on:

Total cases
Total deaths
Average death rate
Average vaccination rate
Correlation Analysis

Used a correlation matrix to examine relationships between COVID-19 cases, deaths, testing, vaccination, and population-based metrics.

📊 Visualizations

The project includes visualizations such as:

Global daily cases and deaths
Top countries by total cases
Top countries by total deaths
Countries with highest death rates
Countries with highest vaccination rates
Cases vs. deaths
Vaccination rate vs. death rate
Correlation heatmap
Continent-wise comparisons
🔍 Key Insights

The analysis helps understand:

How COVID-19 cases and deaths changed globally over time
Differences in COVID-19 impact across countries
The relationship between testing and reported cases
Differences in vaccination coverage
Population-adjusted differences in cases and deaths
Relationships between different COVID-19 indicators

Note: Correlation analysis shows relationships between variables and does not establish causation.

📁 Project Structure
COVID-19-Data-Analysis/
│
├── data/
│   ├── owid-covid-data.xlsx
│   └── cleaned_covid_data.csv
│
├── notebooks/
│   └── COVID-19_Data_Analysis.ipynb
│
├── visualizations/
│
└── README.md
🚀 How to Run
Clone the repository.
Open the project in Jupyter Notebook or VS Code.
Install the required libraries:
pip install pandas numpy matplotlib seaborn openpyxl
Open COVID-19_Data_Analysis.ipynb.
Run the notebook cells sequentially.
👩‍💻 Author

Sakshi Shivaji Chavan

Aspiring Data Analyst | Python | SQL | Power BI | Excel
