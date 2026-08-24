# 📊 GitHub Machine Learning Repositories Analysis

A Data Science project built to collect, clean, store, analyze, and visualize data from public GitHub repositories using the GitHub Search API, SQLite, Pandas, and Matplotlib.

---

## 📁 Project Structure

* `lv3_finalProject_2_Mazen_DECI4_S_418272.ipynb`: Notebook with code for API fetching, analysis, and visualization.
* `github_projects.csv`: Cleaned dataset containing popular Machine Learning repositories.
* `github_projects.db`: SQLite database storing repository details in the `Repositories` table.
* `README.md`: Project documentation and ethics reflection.

---

## 🛠️ Project Tasks Overview

### Task 1: Data Collection Pipeline
* Collected repository data using GitHub REST API.
* Cleaned missing values and extracted nested JSON keys (`owner.login`, `license.name`).
* Formatted datetime fields and saved structured output to `github_projects.csv`.

### Task 2: Store & Analyze Data
* Imported data into a SQLite database (`github_projects.db`).
* Executed SQL queries using filtering, searching (`LIKE`), logical operators (`AND`, `OR`, `NOT`), sorting (`ORDER BY`), aggregate functions (`COUNT`, `AVG`), and grouping (`GROUP BY`, `HAVING`).
* Generated Matplotlib visualizations for Top repositories and trends over time.

### Task 3: Git, GitHub & Ethics
* Applied Git version control for project tracking.
* Published project files and repository structure to GitHub.

---

## 🧠 Ethics Reflection

1. **Why is it important to verify data collected from public APIs?**
   Public API data may contain inconsistencies, missing values, or changing structures. Verifying data ensures accuracy and prevents making incorrect business decisions based on flawed datasets.

2. **Why should data analysts document the source of their data?**
   Documenting data sources ensures transparency, reproducibility, and compliance with API terms of service, allowing others to verify and trust the analytical findings.

3. **How can missing or inaccurate data affect data analysis and decision-making?**
   Inaccurate or incomplete data leads to biased results, skewed statistical summaries, and misleading insights, which can result in faulty strategic choices.
