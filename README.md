# CodeAlpha_TechJobMarketAnalytics

**CodeAlpha Data Analytics Internship — Tasks 1, 2 & 3**

Analyzing the current tech job market by scraping live job postings for three roles — **Data Analyst**,
**Software Engineer**, and **Full Stack Developer** — to understand which skills are most in demand,
where the jobs are, and what experience levels employers expect.

## 📁 Project Structure

```
CodeAlpha_TechJobMarketAnalytics/
├── Task1_WebScraping.ipynb
├── Task2_DataAnalysis.ipynb
├── Task3_Visualization.ipynb
├── india_job_market_2024_2026.csv
├── requirements.txt
└── README.md
```

## 🎯 Objective

Answer: *What does the current tech job market actually want from candidates?*

- Which skills appear most often across Data Analyst / Software Engineer / Full Stack postings?
- How does skill demand differ **between** these three roles?
- Which cities are hiring the most for each role?
- What experience levels are most commonly requested?

## 🛠️ Tools Used

- **Python** — requests, BeautifulSoup (web scraping)
- **Pandas, NumPy** — data cleaning & EDA
- **Matplotlib, Seaborn** — visualization
- **Jupyter Notebook** (via VS Code)

## ✅ Task 1: Web Scraping

Collected ~150 live job postings (~50 per role) from TimesJobs.com, extracting job title, company,
location, experience required, and listed skills for each posting.

## ✅ Task 2: Exploratory Data Analysis

Cleaned the scraped data, checked for missing values, split multi-skill strings into individual
skills, and analyzed skill frequency, location demand, and experience-level patterns — both overall
and broken down by role.

## ✅ Task 3: Data Visualization

Built 5 visualizations: postings by role, top overall skills, a skill-demand heatmap comparing all
three roles side by side, top hiring locations, and experience-level distribution.

## 📊 Key Findings

- The dataset contains 5,000 technology job postings across different roles, locations, experience levels, and industries.
- Data Analyst, Software Engineer, and Full Stack Developer roles were analyzed to identify hiring patterns and skill demand.
- The analysis identified the most frequently requested technical skills across the technology job market.
- Job opportunities were concentrated in major Indian cities, showing strong demand in key technology hubs.
- Different experience levels showed varying levels of demand across job postings.
- Skill co-occurrence analysis highlighted technologies that are frequently requested together by employers.

## 🔗 Links

- **LinkedIn video walkthrough: https://lnkd.in/p/dA-exnzS
- **Internship:** [CodeAlpha](https://www.codealpha.tech)

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Run the notebooks in order: `Task1_WebScraping.ipynb` → `Task2_DataAnalysis.ipynb` →
`Task3_Visualization.ipynb`
