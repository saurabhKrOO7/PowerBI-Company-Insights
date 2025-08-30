<!-- Title -->
<h1 align="center">📊 PowerBI-Company-Insights</h1>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.8%2B-blue">
  <img alt="Web Scraping" src="https://img.shields.io/badge/Web%20Scraping-BeautifulSoup-orange">
  <img alt="Data Cleaning" src="https://img.shields.io/badge/Data%20Cleaning-Pandas-green">
  <img alt="Visualization" src="https://img.shields.io/badge/Visualization-PowerBI-yellow">
</p>

<p align="center">
  🚀 Automated <b>web scraping + data cleaning + Power BI dashboard</b> for generating insights from <b>AmbitionBox company data</b>.
</p>

<hr />

<!-- Highlights -->
<h2>✨ Project Highlights</h2>
<ul>
  <li>✔️ <b>Web Scraping</b> AmbitionBox company pages using Python &amp; BeautifulSoup</li>
  <li>✔️ <b>Data Cleaning</b> and preprocessing with Pandas (handling missing values, type conversions)</li>
  <li>✔️ <b>Interactive Dashboard</b> in Power BI for deep-dive analysis</li>
  <li>✔️ <b>End-to-End Workflow</b>: From raw HTML → clean CSV → beautiful insights</li>
</ul>

<!-- Tech Stack -->
<h2>🛠️ Tech Stack</h2>
<ul>
  <li><b>Language:</b> Python (Jupyter Notebook)</li>
  <li><b>Libraries:</b> <code>requests</code>, <code>beautifulsoup4</code>, <code>pandas</code></li>
  <li><b>Visualization:</b> Microsoft Power BI</li>
  <li><b>Data Format:</b> CSV (<code>ambition_box_data.csv</code>)</li>
</ul>

<!-- Structure -->
<h2>📂 Project Structure</h2>
<pre><code>📦 PowerBI-Company-Insights
├── 📓 WebScrapping_ambitionbox.ipynb   # Notebook: scraping + preprocessing
├── 📊 Ambition Box Data Analytics Dashboard.pbix  # Power BI dashboard
├── 📄 ambition_box_data.csv            # Cleaned dataset
└── 📘 README.md                        # This file
</code></pre>

<!-- Workflow -->
<h2>🚀 Workflow</h2>

<h3>🔎 1) Web Scraping</h3>
<ul>
  <li>Fetched AmbitionBox company data (name, ratings, reviews, industry, etc.)</li>
  <li>Parsed HTML using <b>BeautifulSoup</b></li>
  <li>Handled response issues (<code>403 Forbidden</code>) with custom headers</li>
</ul>

<h3>🧹 2) Data Cleaning</h3>
<ul>
  <li>Removed null/missing values</li>
  <li>Standardized data types</li>
  <li>Exported clean dataset to <code>CSV</code></li>
</ul>

<h3>📊 3) Power BI Dashboard</h3>
<ul>
  <li>Imported dataset into Power BI</li>
  <li>Created visuals:
    <ul>
      <li>⭐ Company rating comparisons</li>
      <li>🏭 Industry trends</li>
      <li>📈 Filterable insights by size, location, rating</li>
    </ul>
  </li>
</ul>

<!-- Preview -->
<h2>📸 Dashboard Preview</h2>
<p><i>(Add a screenshot or GIF here of your Power BI dashboard — this makes the README pop!)</i></p>
<p>
  <!-- Example placeholder (remove if not needed) -->
  <!-- <img src="assets/dashboard-preview.png" alt="Power BI Dashboard Preview" /> -->
</p>

<!-- Getting Started -->
<h2>▶️ Getting Started</h2>

<h3>🔧 Prerequisites</h3>
<ul>
  <li>Python 3.x</li>
  <li>Jupyter Notebook</li>
  <li>Power BI Desktop</li>
</ul>

<h3>📥 Installation</h3>
<pre><code>pip install requests beautifulsoup4 pandas
</code></pre>

<h3>🏃 Run the Notebook</h3>
<pre><code>jupyter notebook WebScrapping_ambitionbox.ipynb
</code></pre>

<h3>📊 Open Dashboard</h3>
<ul>
  <li>Launch <b>Power BI Desktop</b></li>
  <li>Open <code>Ambition Box Data Analytics Dashboard.pbix</code></li>
</ul>

<!-- Why -->
<h2>🌟 Why This Project?</h2>
<ul>
  <li>Automates <b>company insights collection</b></li>
  <li>Reduces manual effort in data gathering</li>
  <li>Turns <b>raw scraped data → actionable insights</b></li>
  <li>Great for <b>job seekers, analysts, and researchers</b></li>
</ul>

<!-- Future -->
<h2>📌 Future Enhancements</h2>
<ul>
  <li>🔄 Schedule periodic scraping (cron jobs / Airflow)</li>
  <li>☁️ Deploy dashboard online (Power BI Service / Streamlit)</li>
  <li>📈 Add salary insights &amp; review sentiment analysis</li>
</ul>

<!-- Contributing -->
<h2>🤝 Contributing</h2>
<p>Contributions, issues, and feature requests are welcome! Feel free to fork and submit a PR 🙌</p>

<!-- Author -->
<h2>💡 Author</h2>
<p>
  👤 <b>Saurabh Kumar</b><br/>
  <a href="https://github.com/saurabhKrOO7">GitHub: saurabhKrOO7</a>
</p>

<hr />
<p align="center"><i>✨ From raw HTML to meaningful insights — powered by Python &amp; Power BI.</i></p>
