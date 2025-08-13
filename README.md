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
<li> <code>Client-Banking</code>
<li> <code>Banking Relationship</code>
<li> <code>Gender</code>
<li> <code>Investment Advisor</code>
<li> <code>Period</code>
</br>
These are joined using primary and foreign keys, following best practices in database normalization.
</br></br>
<h1>🧹 Data Cleaning & Feature Engineering</h1>
</br>
<li> Created new columns:
<li><strong>Engagement Timeframe</strong> – total client relationship length
<li><strong>Engagement Days></strong>  – number of days from account start to today
<li><strong>Income Band</strong> – segmented income levels (Low, Mid, High)
<li><strong>Processing Fees</strong> – fee calculated based on loan size and fee structure


