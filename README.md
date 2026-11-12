# Global Population & Socio-economic Data Analysis

A comprehensive data analysis project examining population demographics, economic indicators, and agricultural metrics across multiple countries using **SQL**, **Python (Pandas, Seaborn, Matplotlib)**, and **Power BI**.

---

## Project Structure :

```text
├── SQL/
│   └── SQL_project (EDA).sql           # Database creation, table schemas, joins, and aggregations
├── Python/
│   └── Population_EDA_Notebook.ipynb   # Data cleaning, exploratory data analysis, and statistical tests
├── PowerBI/
│   └── Population_Report.pbix          # Interactive dashboard and visual reports
└── README.md                           # Project documentation


## Tech Stack & Tools:

- Database Management: MySQL

- Data Processing & Analysis: Python (Pandas, NumPy, Matplotlib, Seaborn)

- Data Visualization: Power BI

- Environment: Google Colab / Jupyter Notebook


1. SQL Exploratory Data Analysis (SQL/):

The SQL module demonstrates core database operations, schema designs, and advanced querying techniques using sample datasets covering country demographics, economic indicators, and food production.

Key Operations Included:
- Database & Table Setup: Creation of Countries and Food Data relational tables with primary keys.

- Filtering & Sorting: Utilizing WHERE, BETWEEN, IN, LIKE, and multi-column ORDER BY clauses.

- Aggregations: Grouping data using GROUP BY and filtering results with HAVING (COUNT, SUM, AVG, ROUND).

- Joins & Set Operations: Implementing INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN (via UNION), CROSS JOIN, and self-joins.


2. Python Exploratory Data Analysis (Python/):

The Python notebook performs an in-depth EDA on population metrics across seven countries, focusing on data hygiene, statistical distributions, and correlation analysis.

Key Analysis Steps:
- Data Inspection: Loading datasets, viewing head/tail samples, checking data types (df.info(), df.describe()).

- Data Cleaning: Identifying and handling missing values (isnull().sum()), removing duplicate records, and handling data inconsistencies.

- Statistical Analysis: Computing central tendencies (mean, median, mode), variance, standard deviation, and correlation matrices (df.corr()).

- Data Visualization: Generating histograms and missing-value heatmaps using Seaborn and Matplotlib to visualize demographic distributions.


3. Power BI Dashboards (PowerBI/):

The Power BI report transforms the raw survey and population datasets into an interactive dashboard, highlighting regional distributions, birth/death rates, and urban population trends.

Enable Data Profiling Tools:
- Open Power BI Desktop, go to Transform Data to open the Power Query Editor. Navigate to the View tab on the top ribbon and check the boxes for Column Quality, Column Distribution, and Column Profile.

Inspect Column Quality & Statistics:
- Click on any column header in Power Query to view its detailed statistics (such as distinct/unique values, null counts, min, max, average, and standard deviation) in the bottom pane

Examine Data Distributions:
- Close Power Query and return to the main report view. Drag numeric and categorical fields onto the canvas using visuals like Histograms, Box & Whisker charts (via custom visuals from AppSource), or Bar Charts to visualize frequency distributions.

Analyze Correlations and Relationships:
- Create a Scatter Chart (placing metrics like GDP on the X-axis and Population or Birth Rate on the Y-axis) and check how data points cluster or disperse.


How to Run This Project:

Run the SQL Queries:
- Open your MySQL client (e.g., MySQL Workbench, phpMyAdmin).
- Import or copy the contents of SQL_project (EDA).sql into your query editor and execute.


Run the Python Notebook (Python/):
To execute the data cleaning and exploratory data analysis notebook:

Step 1: Open Google Colab or your local Jupyter Notebook environment.

Step 2: Upload or open the Population_EDA_Notebook.ipynb file.

Step 3: Install any necessary data analysis packages if they aren't already present by running:

Bash
pip install pandas numpy matplotlib seaborn
Step 4: Run the notebook cells sequentially from top to bottom.


Open and Explore the Power BI Report (PowerBI/):

- Install Power BI Desktop: Ensure you have the latest version of Power BI Desktop installed (free for Windows).

- Open the File: Launch Power BI Desktop, select File > Open report, and browse to open Population_Report.pbix.

Connect/Refresh Data Sources:
- If the report cannot locate the underlying data files automatically, go to Home > Transform Data to open Power Query.

- Update your file paths via Data source settings to point to your local cleaned CSV files.

- Refresh Data: Click the Refresh button on the Home ribbon to pull the latest data into the model and populate your visuals.

 Key Visuals Included:

- Map Visual: Geographic heat map showing population density and regional distribution.

- Bar & Column Charts: Comparative analysis of economic and agricultural production metrics across countries.

- Card Visuals: High-level KPIs displaying total global population, average growth rates, and key metrics at a glance.

##  Author

- Name: Maddy!
- Username: Maddy5625
- GitHub link:(https://github.com/Maddy5625/Project)
