# Hotel-Booking-Analysis

<!-- Title -->
<h1 align="center">Hotel Booking Analysis 🏨📊</h1>
<p align="center">
  Exploratory Data Analysis (EDA) on hotel bookings using <b>Univariate</b> and <b>Bivariate</b> techniques.
</p>

<!-- Badges -->
<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.8%2B-informational">
  <img alt="Jupyter" src="https://img.shields.io/badge/Notebook-Jupyter-orange">
  <img alt="Pandas" src="https://img.shields.io/badge/Data-Pandas-blue">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-green">
</p>

<hr/>

<!-- Overview -->
<h2>📌 Project Overview</h2>
<p>
This project analyzes booking behavior for city and resort hotels to uncover patterns that influence
demand, pricing (ADR), seasonality, and cancellations. The analysis focuses on understanding individual
variable distributions (univariate) and key pairwise relationships (bivariate) that drive business outcomes.
</p>

<!-- Objectives -->
<h2>🎯 Objectives</h2>
<ul>
  <li>Compare demand trends between <b>City Hotel</b> and <b>Resort Hotel</b>.</li>
  <li>Understand cancellation behavior and its drivers (e.g., lead time, ADR).</li>
  <li>Identify seasonal trends, stay patterns, and customer segments.</li>
  <li>Assess the impact of special requests and market segments on bookings.</li>
</ul>

<!-- Dataset -->
<h2>📊 Dataset (Key Columns)</h2>
<ul>
  <li><b>hotel</b> (City Hotel, Resort Hotel)</li>
  <li><b>is_canceled</b> (0/1)</li>
  <li><b>lead_time</b>, <b>adr</b> (Average Daily Rate)</li>
  <li><b>arrival_date_year</b>, <b>arrival_date_month</b>, <b>arrival_date_week_number</b></li>
  <li><b>stays_in_weekend_nights</b>, <b>stays_in_week_nights</b></li>
  <li><b>adults</b>, <b>children</b>, <b>babies</b></li>
  <li><b>market_segment</b>, <b>customer_type</b></li>
  <li><b>total_of_special_requests</b></li>
</ul>

<!-- Methodology -->
<h2>🧭 Methodology</h2>

<h3>1) Data Cleaning & Preparation</h3>
<ul>
  <li>Handled missing and invalid values; standardized date features.</li>
  <li>Created helpful features such as total stay length and total guests.</li>
  <li>Verified numeric distributions and removed obvious outliers where appropriate.</li>
</ul>

<h3>2) Univariate Analysis</h3>
<ul>
  <li>Distributions: <b>lead_time</b>, <b>adr</b>, <b>stay length</b>, <b>special requests</b>.</li>
  <li>Counts: hotel type, market segment, customer type, months &amp; weekdays of arrival.</li>
  <li>Seasonality: monthly booking volume and ADR trends.</li>
</ul>

<h3>3) Bivariate Analysis</h3>
<ul>
  <li><b>lead_time ↔ is_canceled</b> — how early bookings relate to cancellations.</li>
  <li><b>hotel ↔ adr</b> — price differences between City vs Resort hotels.</li>
  <li><b>special_requests ↔ is_canceled</b> — engagement vs cancellation risk.</li>
  <li><b>stay_length ↔ adr</b> — price sensitivity by duration.</li>
  <li><b>month ↔ bookings/adr</b> — seasonality patterns.</li>
  <li><b>market_segment ↔ adr/cancellation</b> — channel-level behavior.</li>
</ul>

<!-- Visuals -->
<h2>📈 Visualizations</h2>
<ul>
  <li>Bar charts for categorical comparisons (hotel type, segments, months).</li>
  <li>Histograms &amp; KDE for numeric distributions (lead time, ADR).</li>
  <li>Box/violin plots for ADR vs hotel/month/segment.</li>
  <li>Heatmaps for correlation overview among numeric variables.</li>
</ul>

<!-- Key Findings -->
<h2>🔎 Key Insights</h2>
<ul>
  <li><b>City Hotels</b> generally receive higher booking volumes than Resort Hotels.</li>
  <li><b>Longer lead times</b> are associated with a <b>higher likelihood of cancellation</b>.</li>
  <li><b>ADR peaks</b> in holiday and high-tourism months; Resort ADR shows stronger seasonality.</li>
  <li>Guests with <b>more special requests</b> tend to <b>cancel less</b> (higher intent to stay).</li>
  <li><b>Market segment</b> and <b>customer type</b> meaningfully shift ADR and cancellation rates.</li>
</ul>

<!-- Tech -->
<h2>🛠️ Tech Stack</h2>
<ul>
  <li><b>Python</b> (Pandas, NumPy)</li>
  <li><b>Matplotlib</b> &amp; <b>Seaborn</b> for visualizations</li>
  <li><b>Jupyter Notebook</b> for analysis</li>
</ul>

<!-- Conclusion -->
<h2>🧾 Conclusion</h2>
<p>
The analysis highlights actionable levers for hotel operations:
optimizing pricing during peak months, proactively managing high–lead time bookings
(to reduce cancellations), and nurturing guests with special requests.
These insights can inform revenue management, marketing targeting, and staffing.
</p>

<!-- Contact -->
<h2>📬 Contact</h2>
<p>
Author: <b>Abhijeet Chandra</b><br/>
GitHub: <a href="https://github.com/abhijeetchandra999">abhijeetchandra999</a>
</p>
