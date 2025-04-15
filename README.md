# NBA Stats Inflation & Era Comparison Project

Welcome to the **NBA Stats Inflation & Era Comparison Project**!  
This project is a deep-dive exploratory data analysis (EDA) into how NBA player statistics have changed over time. It uncovers the key drivers behind the dramatic inflation in offensive output in recent years and makes adjustments to compare players across different eras fairly.

---

## 🏀 Project Objective

The goal of this project is to understand **why** modern NBA statistics are so inflated, **how** the game has evolved, and **what** this means for comparing players across eras. 
This analysis explores:
- 📈 Statistical inflation trends
- 🆚 Techniques to normalize data and compare players across different eras
- ⚡ The impact of pace and offensive efficiency on modern stats  
- 🧩 Changes in game rules and strategies  
- 🌍 The role of globalization in expanding the talent pool  

---

## 🧱 Data Preparation

Multiple datasets from various NBA seasons were cleaned, merged, and transformed. This includes:
- Per-game and per-100 possessions player stats
- Advanced stats
- Team summaries
- Foul and pace metrics
- Award shares

Key data transformation steps:
- Filtering out duplicate player-season entries using "TOT" rows
- Creating per-75 possession metrics
- Calculating **relative true shooting %**
- Normalizing player positions for consistency

---

## 🔍 Exploratory Analysis Highlights

### 📈 1) Stats Changing Over the Years
- Massive increase in 20+ PPG players in recent seasons.
- Points per game have risen sharply, especially since 2015.
- Modern NBA has become **more efficient**, not just faster.

### 🧮 2) Comparing Players Across Eras
- Adjusted stats (e.g., Points per 75 + relative TS%) reveal that many "top scorers" in raw data were inflated by era pace and minutes played.
- Modern players dominating all time scoring rankings.
- Wilt Chamberlain’s 50.4 PPG season drops in relative value when adjusted for pace.

### 🧠 3) Advanced Era Analysis
- Visualization of **pace vs. offensive rating** over time
- 3-point shot revolution tracked by position and volume
- Exploration of players who were ahead of their time 

---

## 📊 Visualizations & Key Charts

The project includes several dynamic and visually intuitive charts, such as:

- 📈 **Number of elite scorers over time**  
- 🔁 **Points per game vs. Pace**  
- 🧠 **Best scoring seasons (PTS per 75 vs. Relative TS%)**  
- 🎯 **3PA per game by position across decades**  
- 📜 **Timeline of rule changes & offensive evolution**

---

## 🧠 Key Takeaways

- The NBA has **evolved tactically, strategically, and culturally**.
- Rule changes (e.g., shot clock, illegal defense, hand-checking) and the **3-point explosion** have played major roles in stat inflation.
- **Efficiency is now king**, not just volume.
- Player comparisons require **era-adjusted context** to be meaningful.

---

## 🧰 Tools & Libraries Used

- **Python**
  - `pandas`, `numpy` for data processing
  - `matplotlib`, `seaborn` for visualizations
- **Jupyter Notebook** for narrative-driven EDA
- **CSV files** as raw data source

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).  
Feel free to fork, modify, or use with proper attribution.
