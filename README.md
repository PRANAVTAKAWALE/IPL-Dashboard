# 🏏 IPL Analysis Dashboard

## 1. Project Title / Headline

**IPL Analytics Dashboard: Comprehensive Match & Performance Insights**

An interactive sports analytics dashboard built using Power BI to analyze Indian Premier League (IPL) data across multiple seasons, uncovering trends in team performance, scoring patterns, toss decisions, venues, and match outcomes.

---

## 2. Short Description / Purpose

The IPL Analytics Dashboard is a data visualization and exploratory analytics project designed to analyze historical IPL match and ball-by-ball data. It helps users understand season-wise trends, team dominance, scoring behavior, and strategic factors such as toss decisions and venue impact, enabling data-driven insights in the domain of sports analytics.

---

## 3. Tech Stack

The dashboard was built using the following tools and technologies:

- **Power BI Desktop** – Primary platform for building interactive dashboards and reports  
- **Power Query** – Used for data cleaning, transformation, and preprocessing  
- **DAX (Data Analysis Expressions)** – Created calculated measures such as total runs, wickets, averages, win margins, and KPIs  
- **Data Modeling** – Relationship modeling between matches and deliveries datasets  
- **Data Format** – CSV / Excel files (`matches.xlsx`, `deliveries.xlsx`)  
- **Dashboard Output** – `.pbix` report and `.png` dashboard snapshot  

---

## 4. Data Source

**Source:** IPL Historical Match Data  

The analysis is based on two structured datasets:

- **Matches Dataset** – Match-level information such as season, teams, toss, venue, result, and winner  
- **Deliveries Dataset** – Ball-by-ball data capturing runs, wickets, bowlers, batsmen, dismissals, and extras  

Together, these datasets enable both high-level season analysis and granular player-level insights across multiple IPL seasons.

---

## 5. Features / Highlights

### Business Problem

IPL generates massive volumes of match and performance data every season. However, raw data alone makes it difficult to answer strategic questions such as:

- How have scoring patterns evolved over seasons?  
- Does winning the toss significantly influence match outcomes?  
- Which teams and venues consistently perform better?  
- What are the dominant win patterns—by runs or by wickets?  

Without an interactive analytical tool, extracting these insights becomes time-consuming and inefficient.

---

### Goal of the Dashboard

The primary goal of this dashboard is to:

- Provide a centralized visual analytics platform for IPL data  
- Enable season-wise, venue-wise, and team-wise exploration  
- Identify patterns, trends, and strategic factors influencing match results  
- Support sports analytics, decision-making, and storytelling through data  

---

### Walkthrough of Key Visuals

#### Key KPIs (Top Section)

High-level performance indicators displayed prominently:

- Total Seasons: 10  
- Total Matches: 636  
- Average Runs per Match: 305.53  
- Total Runs: 194K  
- Total Wickets: 7,438  
- Total Sixes: 6,523  
- Total Fours: 17K  

These KPIs provide an instant snapshot of the scale and intensity of IPL matches.

---

#### Season & Venue Filters

- Interactive season slicer (2008–2016)  
- Venue filter to analyze performance across different stadiums  

All visuals dynamically update based on selected filters.

---

#### Toss Decision Analysis (Donut Chart)

- Comparison of bat vs field decisions after winning the toss  
- Highlights strategic preferences and evolving match tactics  

---

#### Total Runs by Season (Bar Chart)

- Season-wise aggregation of total runs  
- Identifies high-scoring seasons and overall scoring growth trends  

---

#### Average Runs by Season (Line Chart)

- Tracks scoring consistency and volatility across seasons  
- Useful for understanding changes in pitch behavior and playing style  

---

#### Win Type Analysis (Stacked Bar Chart)

- Matches won by runs vs by wickets  
- Reveals dominance patterns and chasing vs defending effectiveness  

---

#### Matches by City (Map Visualization)

- Geographic distribution of IPL matches  
- Helps identify major IPL hubs and high-frequency venues  

---

#### Most Successful Teams (Bar Chart)

- Ranking of teams based on matches won  
- Highlights historically dominant franchises  

---

### Business Impact & Insights

#### Strategic Analysis
- Teams chasing targets show strong win trends in certain seasons  
- Toss decisions lean more toward fielding, indicating chasing advantages  

#### Venue Intelligence
- Certain cities consistently host more matches, making them strategic hubs  

#### Performance Trends
- Increase in average runs over seasons reflects aggressive batting evolution  

#### Decision Support
- Useful for analysts, coaches, and strategists for performance benchmarking  
- Enables data-driven storytelling for presentations and fan engagement  

---

**Dashboard Preview:**  
## 6. Screenshots / Demos

![IPL Analytics Dashboard](IPL_Dashboard_Snapshot.png)


