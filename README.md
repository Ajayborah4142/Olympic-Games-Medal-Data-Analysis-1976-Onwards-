# Olympic Games Medal Data Analysis (1976 – Onwards)

**Project Title:** Olympic Games Medal Data Analysis (1976 – onwards)

**Notebook/Script:** `Olympic_Games_Medal_Analysis.ipynb` or `.sql`

---

## 🏅 Project Overview

This project focuses on analyzing the performance of **countries**, **athletes**, and **disciplines** in the **Summer Olympic Games (1976 onwards)** using a dataset of medal records. The analysis is conducted primarily using **SQL queries** after storing the dataset in a **relational database (MySQL or PostgreSQL)**.

The dataset includes information about:

* 🏙️ **Host city** and **year** of the Olympics
* 🏃‍♂️ **Sports** and **disciplines** (e.g., Diving, Athletics)
* 🥇 **Events** and their **genders**
* 👨‍🦱 **Athletes** and their **countries**
* 🏆 **Medals** (Gold, Silver, Bronze)

---

## 🎯 Objectives of the Project

### 1. Country & Performance Insights

* Identify dominant countries in specific sports (e.g., Diving in 2008)
* Compare medal tallies between leading nations (China, Russia, Germany, Australia)
* Detect emerging countries that achieved new medal milestones

### 2. Gender & Equality Insights

* Compare **men vs. women** medal distributions
* Identify **countries excelling in women’s participation**
* Detect **events dominated by a single gender**

### 3. Event & Discipline Insights

* Discover **medal-rich events** and **top-performing disciplines**
* Compare **synchronized vs. individual** event medals
* Highlight **multi-event athletes** who have won multiple medals

---

## 🔍 Tools & Technologies Used

| Category               | Tools/Technologies                           |
| ---------------------- | -------------------------------------------- |
| Database               | MySQL / PostgreSQL                           |
| Analysis               | SQL Queries, Aggregations, Joins, Subqueries |
| Visualization          | Power BI / Tableau / Matplotlib (optional)   |
| Programming (optional) | Python (Pandas, SQLAlchemy, Matplotlib)      |
| Documentation          | Jupyter Notebook / README.md                 |

---

## ⚙️ Project Workflow

1. **Data Loading:** Import the Olympic medals dataset into SQL database tables.
2. **Database Design:** Create normalized tables for `athletes`, `countries`, `events`, `disciplines`, and `medals`.
3. **Data Cleaning:** Remove duplicates, standardize names, and fix data types.
4. **Exploratory Analysis using SQL:**

   * Medal counts by country, sport, and year
   * Gender-based participation and medal ratios
   * Country-specific strengths and weaknesses
5. **Advanced Analysis:**

   * Identify top-performing athletes and multi-event winners
   * Analyze time trends (1976–present)
   * Compare regional dominance (Asia, Europe, etc.)
6. **Visualization & Insights:** Create dashboards or charts summarizing medal performance and equality trends.

---

## 📊 Key Insights & Outcomes

* 🥇 **Dominant Countries:** China and the USA lead overall, with noticeable rises from Japan and Great Britain post-2000.
* 👩‍🦱 **Gender Equality:** Women’s participation has significantly increased since 1992, closing the gap in total medals.
* 🏊 **Sport-Specific Strengths:**

  * Diving and Gymnastics are dominated by China and the USA.
  * Athletics shows consistent global competitiveness.
* 🏅 **Multi-Medal Athletes:** Identified athletes who achieved repeat success across multiple Olympic Games.

---

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Olympic-Games-Medal-Analysis.git
   cd Olympic-Games-Medal-Analysis
   ```

2. Import dataset into SQL:

   ```sql
   LOAD DATA INFILE 'data/olympic_medals.csv' INTO TABLE medals
   FIELDS TERMINATED BY ',' IGNORE 1 ROWS;
   ```

3. Execute analysis queries from `sql_queries/analysis_queries.sql`

4. (Optional) Open the Jupyter Notebook for visual analysis:

   ```bash
   jupyter notebook notebooks/Olympic_Games_Medal_Analysis.ipynb
   ```

---

## 📈 Visualization Ideas

* Medal tally by country and year (bar chart)
* Top 10 athletes by total medals (horizontal bar chart)
* Gender participation trend over time (line chart)
* Medal distribution by sport and continent (heatmap)

---

## 🧭 Key Outcomes

* Provided **strategic insights** into historical Olympic performances.
* Highlighted **gender equality trends** across multiple sports.
* Uncovered **patterns of dominance** and **emerging countries**.
* Built a foundation for **future forecasting** in sports analytics.

---

## 💡 Future Enhancements

* Integrate machine learning to predict next Olympics medal trends.
* Build Power BI dashboards for interactive exploration.
* Include Winter Olympics data for full comparison.
* Add scraping pipeline to update medal data automatically.

---

## 👤 Author

**Created by:** Ajay Borah
**GitHub:** [Ajayborah4142](https://github.com/Ajayborah4142)

---


