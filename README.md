# CodeAlpha_TechJobMarketAnalytics

**CodeAlpha Data Analytics Internship — Tasks 1, 2 & 3**

Analyzing the current tech job market by scraping live job postings for three roles — **Data Analyst**,
**Software Engineer**, and **Full Stack Developer** — to understand which skills are most in demand,
where the jobs are, and what experience levels employers expect.

## 📁 Project Structure

```
CodeAlpha_TechJobMarketAnalytics/
├── Task1_WebScraping.ipynb      # Scrapes job postings from TimesJobs.com
├── Task2_DataAnalysis.ipynb     # Exploratory Data Analysis (EDA)
├── Task3_Visualization.ipynb    # Charts and visual insights
├── jobs_data.csv                # Raw scraped data
├── jobs_data_cleaned.csv        # Cleaned data (output of Task 2)
├── chart1_postings_by_role.png
├── chart2_top_skills_overall.png
├── chart3_skills_heatmap.png
├── chart4_top_locations.png
├── chart5_experience_levels.png
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

*(Fill this in after running the notebooks — 4-6 bullet points on your actual results.)*

- ...
- ...
- ...

## 🔗 Links

- **LinkedIn video walkthrough:** *(add link here)*
- **Internship:** [CodeAlpha](https://www.codealpha.tech)

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Run the notebooks in order: `Task1_WebScraping.ipynb` → `Task2_DataAnalysis.ipynb` →
`Task3_Visualization.ipynb`
