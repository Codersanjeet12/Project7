# Project7
Project 7 Dashboards
# 🏏 Cricket Ball-by-Ball Analysis | Power BI Dashboard

An interactive **Power BI dashboard** built on ball-by-ball cricket data to explore batting patterns, batter vs bowler match-ups, extras and innings contribution. Click on any visual and the rest of the report filters automatically.

## 📌 Project Overview

Ball-by-ball data has a lot of detail but is hard to read in raw form. This project turns it into simple visuals so that questions like *"Which batters face the most bowlers?"*, *"How do right-hand and left-hand batters compare?"* and *"How do extras and runs split across innings?"* can be answered in a few clicks.

## 📊 Dashboard Visuals

| Visual | What it shows |
|---|---|
| **Sum of ball_number by batsman_type** | Right-hand vs left-hand batter comparison |
| **Count of bowler by batter** | Number of bowlers each batter has faced, sorted high to low (Kohli, Dhawan, Rohit Sharma, Warner, Raina, Dhoni and more) |
| **Penalty, super over, wicket, wide ball and non-striker counts by is_no_ball** | Breakdown of special delivery events for no-ball vs normal deliveries |
| **Donut chart: extras, innings and batter_runs** | Share of extras, innings and batter runs |
| **Map visual (overs)** | Location-based view of overs |

## ✨ Key Features

- Fully **interactive**: cross-filtering between all visuals
- Batter-wise drill-down using the bowler count chart
- Clean, colour-coded layout for quick reading
- Built using the Power BI Desktop report canvas

## 🛠️ Tools & Skills Used

- **Power BI** (visuals, filters, report design)
- **Data modelling and cleaning**
- **Data visualisation and storytelling**
- Python / Pandas and SQL for data preparation

## 📂 Repository Structure

```
├── README.md
├── dashboard.pbix          # Power BI report file
├── data/                   # Dataset (CSV)
└── screenshots/            # Dashboard images and demo recording
```

## ▶️ How to Use

1. Download or clone this repository.
2. Open `dashboard.pbix` in **Power BI Desktop**.
3. Click any bar, slice or batter name to filter the other visuals.
4. Use the filter pane to explore further.

## 🎥 Demo

Add a screenshot or GIF of the dashboard here:

```
![Dashboard Preview](screenshots/dashboard.png)
```

## 🔍 Insights

- Right-hand batters account for far more deliveries than left-hand batters in the data.
- A small group of top batters has faced the highest number of different bowlers.
- Most deliveries are normal (not no-ball), and extras form a small share compared to batter runs.

## 🚀 Future Improvements

- Add season-wise and team-wise filters
- Add strike rate, average and economy rate measures
- Replace the map visual with a venue or team analysis
- Publish the report to Power BI Service

## 👤 Author

**Sanjeet Kumar**
Aspiring Data Analyst | Python • SQL • Power BI • Excel

📍 India
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) | 💻 [GitHub](https://github.com/your-username)

⭐ If you found this useful, consider giving the repo a star!
