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
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>KPIs Box</title>
</head>
<body style="margin:0;background:#f5f6f8;font-family:Arial,Helvetica,sans-serif">
  <div style="max-width:880px;margin:24px auto;padding:20px;background:#fff;border:1px solid #d9d9d9;border-radius:10px;box-shadow:0 2px 6px rgba(0,0,0,.08)">
    <div style="font-size:20px;font-weight:700;display:flex;gap:10px;align-items:center;margin-bottom:14px">
      <span>📊</span> <span>Key KPIs and DAX Metrics</span>
    </div>

    <table style="width:100%;border-collapse:collapse;font-size:14px">
      <thead>
        <tr>
          <th style="text-align:left;padding:10px;border:1px solid #e3e3e3;background:#f3f4f6;width:200px">KPI</th>
          <th style="text-align:left;padding:10px;border:1px solid #e3e3e3;background:#f3f4f6">Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td style="padding:10px;border:1px solid #e3e3e3;font-weight:700">Total Clients</td>
          <td style="padding:10px;border:1px solid #e3e3e3">Count of unique client IDs</td>
        </tr>
        <tr>
          <td style="padding:10px;border:1px solid #e3e3e3;font-weight:700">Total Loan</td>
          <td style="padding:10px;border:1px solid #e3e3e3">Bank Loan + Business Lending + Credit Card Balance</td>
        </tr>
        <tr>
          <td style="padding:10px;border:1px solid #e3e3e3;font-weight:700">Total Deposits</td>
          <td style="padding:10px;border:1px solid #e3e3e3">Sum of Savings, Bank, Checking, and Foreign Currency Accounts</td>
        </tr>
        <tr>
          <td style="padding:10px;border:1px solid #e3



