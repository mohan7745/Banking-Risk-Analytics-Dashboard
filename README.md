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

| KPI               | Description |
|-----------------------|-----------------|
| Total Clients       | Count of unique client IDs |
| Total Loan          | Bank Loan + Business Lending + Credit Card Balance |
| Total Deposits      | Sum of Savings, Bank, Checking, and Foreign Currency Accounts |
| Processing Fees     | Loan amount × processing rate |
| Engagement Days     | Days between joining and today |
| Credit Card Balance | Total current credit card debt across all clients |
| Bank Deposit        | Total deposited amount across bank accounts |
</br></br></br>

All KPIs were calculated using DAX formulas like <code>SUM</code> , <code>SUMX</code> , <code> DISTINCTCOUNT</code> , <code>DATEDIFF</code> and  <code>SWITCH</code> .
</br></br>
<h1>📊 Dashboards</h1>
<h3>🏠 Home Dashboard</h3>
High-level summary with filters by gender, nationality, and income band.</br></br>
<img width="1280" height="745" alt="image" src="https://github.com/mohan7745/Banking-Risk-Analytics-Dashboard/blob/main/br2.jpg?raw=true" />
</br></br>
<h1>💰 Loan Analysis</h1>
Breakdown of loan type, amount, default risk, and credit balances.
</br></br>
<img width="1280" height="745" alt="image" src="https://github.com/mohan7745/Banking-Risk-Analytics-Dashboard/blob/main/br3.jpg?raw=true" />
</br></br>
<h1>🏦 Deposit Analysis</h1>
Visualization of client deposits across all account types.
</br></br>
<img width="1280" height="745" alt="image" src="https://github.com/mohan7745/Banking-Risk-Analytics-Dashboard/blob/main/Br4.jpg?raw=true"/>
</br></br>
<h1>📋 Summary Dashboard</h1>
Interactive summary with client segmentation, engagement, and advisor data.
</br></br>
<img width="1280" height="745" alt="image" src="https://github.com/user-attachments/assets/7698988f-1c21-4d3a-aab1-d4ae09eaca8b" />

</br></br>
<h1>✅ Insights & Observations</h1>
<li>📈 Private banks have the highest client counts and total loans issued</br>
<li>💳 Foreign nationals tend to hold larger loan balances</br>
<li>🔄 High-income clients show longer engagement and more deposits</br>
<li>⚠️ Processing fees vary significantly by fee structure and loan type</br>


