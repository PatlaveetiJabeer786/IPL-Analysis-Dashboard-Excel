# 🏏 IPL Analysis Dashboard (2008–2022)

[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1a0533,30:4a0080,60:0047ab,100:004d99&height=230&section=header&text=IPL%20Analysis%20Dashboard&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=15%20Seasons%20%7C%202008%E2%80%932022%20%7C%20Excel%20%7C%20Pivot%20Tables%20%7C%20Power%20Query%20%7C%20Slicers&descAlignY=58&descSize=15)](https://github.com/PatlaveetiJabeer786/IPL-Analysis-Dashboard-Excel)

<div align="center">

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot%20Tables-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Sports%20Analytics-FF6B00?style=for-the-badge)
![Seasons](https://img.shields.io/badge/IPL%20Seasons-2008%20to%202022-blueviolet?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed%20✅-brightgreen?style=for-the-badge)

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════╗
║  🏆  15 SEASONS  •  900+ MATCHES  •  100% EXCEL  •  FULLY INTERACTIVE  ║
╚══════════════════════════════════════════════════════════════════════════╝
```

</div>

---

## 📌 Project Overview

This is a **complete, interactive IPL Analysis Dashboard** built entirely in **Microsoft Excel** — covering **15 seasons of Indian Premier League cricket from 2008 to 2022**.

The Indian Premier League is not just a cricket tournament — it is a **multi-billion dollar sports business** involving franchises, broadcasters, sponsors, and millions of fans. Every season generates massive volumes of match data that holds the answers to critical performance, strategy, and investment questions.

This project transforms that **raw, complex match data into a clean, dynamic Excel dashboard** — featuring Pivot Tables, Power Query ETL, interactive Slicers, and rich charts — giving cricket analysts, team strategists, and sports fans a **single-screen view of 15 years of IPL history**.

---

## 🧩 Business Problem

> *"IPL franchises, broadcasters, and sports analysts had access to 15 years of raw match data — but it was scattered, unstructured, and impossible to explore interactively. Questions like 'Which team wins the most batting first?', 'Which venue is a fortress for the home team?', or 'Who won the Player of the Season in 2016?' required hours of manual lookup. There was no single dashboard to answer them all."*

**The key questions this project was built to answer:**

- 🏆 Who won each IPL season from 2008 to 2022?
- 🥈 Who were the runners-up in each season?
- 🌟 Who won Player of the Season each year?
- 🏟️ Where was each IPL final played?
- 🎯 Which teams win more when they bat first vs field first?
- 🪙 How does winning the toss affect the match result?
- 🏟️ Which are the Top 10 venues by matches won?
- 🏅 Which team has the most IPL wins across all seasons?

---

## 🎯 My Task as the Data Analyst

| Task | What I Did | Tool Used |
|------|-----------|----------|
| **Data Import** | Loaded raw IPL match data (2008–2022) into Excel | Excel / Power Query |
| **Data Cleaning** | Removed nulls, fixed team name inconsistencies, standardized columns | Power Query |
| **Data Transformation** | Reshaped data — added season, venue, and result columns | Power Query (M Language) |
| **Pivot Table Analysis** | Built all summary tables — wins by team, toss analysis, venue stats | Pivot Tables |
| **KPI Cards** | Season Winner, Runner-Up, Player of Season, Final Venue — per year | Excel Formulas + Slicers |
| **Charts & Visuals** | Bar charts, pie charts, donut charts for wins, toss, venue stats | Excel Charts |
| **Interactive Slicers** | Season slicer — entire dashboard filters with one click | Excel Slicers |
| **Dashboard Design** | Assembled all visuals into a single, clean dashboard sheet | Excel |

---

## 📊 Dashboard Preview

![IPL Dashboard](IPL_Dashboard.png)

*👆 The Interactive IPL Excel Dashboard — Season KPIs + Toss Analysis + Venue Stats + Team Rankings — all connected via Slicers*

---

## 📈 Dashboard KPIs — What I Tracked

<div align="center">

| KPI Card | What It Shows | Example (2022) |
|----------|--------------|----------------|
| 🏆 **Winner of Season** | IPL Champion for the selected year | Gujarat Titans |
| 🥈 **Runner-Up** | Team that finished second | Rajasthan Royals |
| 🌟 **Player of the Season** | Best performing player | Jos Buttler |
| 🏟️ **Final Match Venue** | Stadium where the final was played | Narendra Modi Stadium |

</div>

---

## 🔍 My Workflow — Step by Step

### ✅ Step 1 — Data Import & Cleaning (Power Query)

- Loaded the raw `IPL Matches 2008-2022.xlsx` dataset into **Power Query**
- Cleaned all inconsistencies — team name variations (e.g. *"Delhi Daredevils"* vs *"Delhi Capitals"*) standardized across all 15 seasons
- Removed null rows and incomplete match records
- Added calculated columns — **Season Year**, **Match Result Type**, **Toss Winner = Match Winner** flag
- Loaded clean data back to Excel for Pivot Table analysis

---

### ✅ Step 2 — Pivot Table Analysis

Built the following Pivot Tables as the engine behind every dashboard visual:

```
Pivot Table 1 → Season-wise Winner & Runner-Up (filtered by Slicer)
Pivot Table 2 → Total Wins by Team (all seasons combined)
Pivot Table 3 → Wins by Toss Decision (Bat First vs Field First)
Pivot Table 4 → Toss Win → Match Win conversion rate
Pivot Table 5 → Top 10 Venues by Total Matches Won
Pivot Table 6 → Season-wise Player of the Season
Pivot Table 7 → Final Match Venue per Season
```

---

### ✅ Step 3 — Dashboard Visuals I Built

| Visual | Type | What It Shows |
|--------|------|--------------|
| 🏆 **Season KPI Cards** | Excel Cards | Winner, Runner-Up, Player of Season, Final Venue |
| 📊 **Wins by Team** | Horizontal Bar | All-time wins ranking across every IPL team |
| 🥧 **Toss Decision** | Pie / Donut Chart | % of teams choosing to Bat First vs Field First after winning toss |
| 📊 **Toss Impact** | Bar Chart | Whether winning the toss actually helps win the match |
| 🏟️ **Top 10 Venues** | Horizontal Bar | Venues ranked by total matches won — home fortress analysis |
| 📅 **Season Slicer** | Interactive Slicer | Filters the entire dashboard for any season from 2008 to 2022 |

---

## 💡 Key Business Insights & Outcomes

### 🏆 Championship Insights
- **Mumbai Indians** are the most successful franchise — highest total wins and most IPL titles
- **Chennai Super Kings** have the most consistent performance — finalist appearances across multiple decades
- **Kolkata Knight Riders** and **Rajasthan Royals** have shown strong revival seasons after rebuilding phases

### 🪙 Toss Strategy Insights
- Teams winning the toss **predominantly choose to field first** — chasing is the preferred strategy in T20 cricket
- **Toss advantage is overrated** — winning the toss does NOT guarantee a match win across all seasons
- Certain venues show a **stronger correlation between toss outcome and match result** — venue-specific data changes strategy

### 🏟️ Venue Analysis
- **Wankhede Stadium (Mumbai)** and **Eden Gardens (Kolkata)** are among the most matches-hosting venues — home advantage is real
- Certain neutral venues (used for playoffs) show more balanced win rates between teams
- **Final venue history** reveals IPL's rotation of major stadiums across India over 15 seasons

### 📅 Season-by-Season Trends
- **2013–2016** was Mumbai Indians' dominant era — back-to-back titles showing squad consistency
- **2022** marked the rise of new franchises — Gujarat Titans winning in their debut season is historically unique
- Player of the Season awards show the rise of **T20 specialists** — players with high strike rates and economy rates dominate

---

## 📈 Business Value Delivered

| Business Question | Before This Dashboard | After This Dashboard |
|-------------------|-----------------------|----------------------|
| Who won in 2019? | Manual lookup in raw data | One-click Slicer → instant answer |
| Best toss strategy? | No analysis available | Pie chart shows Bat vs Field trends |
| Top performing venues? | Buried in 900+ rows | Ranked bar chart — visible instantly |
| Player of the Season history? | Not tracked across seasons | KPI card changes per season selected |
| Which team to invest in? | Guesswork | All-time win table shows dominant franchises |
| How has IPL grown? | No single view | Season-by-season comparison with Slicer |

---

## 📁 Project Structure

```
IPL-Analysis-Dashboard-Excel/
│
├── IPL Matches 2008-2020.xlsx       # Raw dataset — all IPL matches (2008–2022)
├── IPL_Dashboard.png                # Dashboard screenshot
└── README.md
```

---

## 🚀 How to Run This Project

1. **Download** this repository to your local machine

2. **Open** `IPL Matches 2008-2020.xlsx` in **Microsoft Excel**
   *(Excel 2016 or later recommended for full Pivot Table + Slicer support)*

3. **Navigate to the Dashboard sheet** — it's the main visual sheet

4. **Use the Season Slicer** on the left to select any year from **2008 to 2022**
   - All KPI cards, charts, and tables update automatically

5. **Explore the Pivot sheets** to see the raw aggregations behind each visual

> 💡 **Tip:** Enable **Macros** if prompted — required for full slicer interactivity in some Excel versions

---

## 🧠 Key Technical Skills Demonstrated

```
✅  Power Query ETL           — Import, clean & transform 900+ match records
✅  M Language transformations — Standardized team names across 15 seasons
✅  Pivot Tables               — 7 pivot tables powering every dashboard visual
✅  Excel Slicers              — Connected to all pivot tables for one-click filtering
✅  KPI Card Design            — Dynamic cards showing Season Winner, MVP, Venue
✅  Excel Charts               — Bar, Pie, Donut charts with conditional formatting
✅  Dashboard Layout           — Single-sheet professional dashboard design
✅  Sports Domain Knowledge    — Understanding IPL formats, toss rules, season structure
✅  Data Storytelling          — 15 seasons of cricket history told through visuals
```

---

## 🏅 IPL Season Winners — Quick Reference

<div align="center">

| Season | 🏆 Winner | 🥈 Runner-Up |
|--------|----------|-------------|
| 2008 | Rajasthan Royals | Chennai Super Kings |
| 2009 | Deccan Chargers | Royal Challengers Bangalore |
| 2010 | Chennai Super Kings | Mumbai Indians |
| 2011 | Chennai Super Kings | Royal Challengers Bangalore |
| 2012 | Kolkata Knight Riders | Chennai Super Kings |
| 2013 | Mumbai Indians | Chennai Super Kings |
| 2014 | Kolkata Knight Riders | Kings XI Punjab |
| 2015 | Mumbai Indians | Chennai Super Kings |
| 2016 | Sunrisers Hyderabad | Royal Challengers Bangalore |
| 2017 | Mumbai Indians | Rising Pune Supergiant |
| 2018 | Chennai Super Kings | Sunrisers Hyderabad |
| 2019 | Mumbai Indians | Chennai Super Kings |
| 2020 | Mumbai Indians | Delhi Capitals |
| 2021 | Chennai Super Kings | Kolkata Knight Riders |
| 2022 | Gujarat Titans | Rajasthan Royals |

</div>

---

## 🌟 Final Summary

| 🔴 Problem | 🟢 My Solution | 📈 Result |
|-----------|---------------|----------|
| 900+ raw match rows — no insights | Power Query ETL + 7 Pivot Tables | Clean, structured analysis |
| No season-by-season view | Interactive Season Slicer | Full 15-year history explorable |
| No KPI tracking | Dynamic KPI cards per season | Winner, MVP, Venue — instant |
| No toss strategy insight | Toss decision pie + impact bar chart | Data-backed fielding/batting decision |
| No venue analysis | Top 10 venues ranked by wins | Home advantage quantified |
| Complex raw cricket data | Single-sheet Excel dashboard | Anyone can explore — no SQL needed |

---

## 👨‍💻 About Me

I'm a Data Analyst passionate about turning complex sports and business data into clear, interactive dashboards that anyone can explore and understand.

- 🔗 **LinkedIn:** [linkedin.com/in/jabeer-patlaveeti](https://linkedin.com/in/jabeer-patlaveeti)
- 📧 **Email:** jabeerpatlaveeti@gmail.com
- 🌐 **GitHub:** [github.com/PatlaveetiJabeer786](https://github.com/PatlaveetiJabeer786)

---

<div align="center">

⭐ **If this project impressed you, please give it a Star — it helps others discover it!** ⭐

*Dataset: IPL Match Data 2008–2022 from Kaggle. Project built for educational and portfolio purposes.*

</div>

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1a0533,30:4a0080,60:0047ab,100:004d99&height=120&section=footer)](https://github.com/PatlaveetiJabeer786/IPL-Analysis-Dashboard-Excel)
