# Banking-Risk-Analytics-Dashboard

A full-stack banking analytics project using Power BI, MySQL, Python, and Excel to analyze client behavior, assess loan risk, and create interactive dashboards for data-driven decision-making.
<img width="1280" height="745" alt="image" src="https://github.com/user-attachments/assets/7698988f-1c21-4d3a-aab1-d4ae09eaca8b" />
</br>
<h1>🧠 Problem Statement</h1></br>
Banks face increasing risk when lending to unqualified customers. The goal of this project is to develop a risk analytics system that helps financial institutions make smarter decisions on loan approvals based on historical banking behavior and customer profiles.
</br>
<h1>💡 Solution Overview</h1></br>
This project processes and analyzes relational banking data to:
</br></br>
<li>Assess loan default risk</li>
<li>Segment clients by income and engagement</li>
<li>Track and visualize key KPIs</li>
<li>Support real-time loan decision-making through dashboards
</br></br>
The entire pipeline uses:
</br></br>
<li>Excel for initial data exploration</li>
<li>Python for data cleaning and feature engineering</li>
<li>MySQL for relational data querying</li>
<li>Power BI for KPI dashboard development</li>
</br>
<h1>💻 Technologies Used</h1>
</br>
<li><strong>Power BI </strong> – Interactive dashboards and data visualizations</li>
<li><strong>MySQL</strong>– Data extraction, joins, and aggregations
<li><strong>Python (Pandas, NumPy)</strong> – Preprocessing and custom metric creation
<li><strong> Excel </strong>– Early-stage data analysis and profiling
</br>
<h1>📂 Dataset Overview</h1>
The project uses a multi-table relational database with the following key tables:
</br></br>
<li> <code>Client-Banking</code>
<li> <code>Banking Relationship</code>
<li> <code>Gender</code>
<li> <code>Investment Advisor</code>
<li> <code>Period</code>
</br></br>
These are joined using primary and foreign keys, following best practices in database normalization.
</br></br>
<h1>🧹 Data Cleaning & Feature Engineering</h1>
</br></br>
<strong>Created new columns:</strong>
<li><strong>Engagement Timeframe</strong> – total client relationship length
<li><strong>Engagement Days</strong>  – number of days from account start to today
<li><strong>Income Band</strong> – segmented income levels (Low, Mid, High)
<li><strong>Processing Fees</strong> – fee calculated based on loan size and fee structure
</br></br>
<strong>Used Python for:</strong>
<li> Merging and transforming raw data
<li> Calculating DAX-ready columns for Power BI
<li> Handling missing values and outliers
</br>
<li>Stored final cleaned data in <strong>MySQL</strong> for Power BI import
</br></br>
<h1>🧮 Key KPIs and DAX Metrics</h1>
        <strong>KPI</strong>
<code>Total Clients</code></br>               Count of unique client IDs
<code>Total Loan</code></br>                  Bank Loan + Business Lending + Credit Card Balance
<code>Total Deposits</code></br>              Sum of Savings, Bank, Checking, and Foreign Currency Accounts 
<code>Processing Fees</code></br>             Loan amount × processing rate 
<code>Engagement Days</code></br>             Days between joining and today                 
<code>Credit Card Balance</code></br>         Days between joining and today           


