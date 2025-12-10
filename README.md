# 🎧 Spotify 2025 Global Music Market Analysis

## 🎯 Project Overview

This project focuses on performing deep **Data Mining** on the latest Spotify music data (Year 2025) to derive clear, non-technical, and actionable insights for business investment and music production strategy. The goal was to move beyond simple reporting and identify the characteristics of success in the current global market.

The entire analysis is constrained strictly to the 2025 release data.

## 📊 Data Source

* **Dataset:** Spotify Global Music Dataset (2025 Subset)
* **File Used:** `spotify_data clean.csv`
* **Key Metrics Used:** `track_popularity`, `track_duration_min`, `artist_popularity`, `artist_genres`.

## 🛠️ Methodology (Data Mining)

The analysis was performed entirely using **Python** (Pandas) to clean, filter, and aggregate the raw data into business-ready summary tables.

### Tools & Libraries
* **Python:** Data cleaning and aggregation.
* **Pandas:** Data manipulation.

### Phases
1.  **Data Preparation:** Loaded data, converted date formats, and strictly filtered to ensure **only 2025 records** were analyzed. Handled missing values in core metrics.
2.  **Insight Generation:** Calculated key performance metrics across defined tiers (quantiles) and groups (genres/artists).
3.  **Output:** Generated three clean CSV files for direct consumption by Power BI.

## ✨ Key Insights (The Results)

The analysis was structured around three core business questions, with the following actionable findings:

| Focus Area | Insight / Conclusion | Actionable Data |
| :--- | :--- | :--- |
| **Artist Investment** | **The Safe Bet Pays Off:** Superstars' new releases are **68% more popular** on average than those by Mid-Tier/Newcomers. | Prioritize established talent for highest track popularity return. |
| **Production Length** | **The Extra Minute Pays:** The **Top 25% most popular songs** in 2025 are noticeably longer ($3.28$ minutes) than the average release ($3.00$ minutes). | Don't rush a potential hit; give it the runtime it needs. |
| **Genre Performance** | **K-Pop Leads Engagement:** Among the most frequent genres released, K-Pop delivered the **highest average track popularity score**. | Focus marketing spend on high-engagement genres. |

## 🖥️ Visualization

The final findings were translated into a high-impact, easy-to-read dashboard using **Power BI** to ensure clarity for non-technical stakeholders.

### Power BI Artifacts
* `01_duration_vs_popularity_2025.csv`
* `02_genre_popularity_2025.csv`
* `03_artist_investment_2025.csv`

---
<img width="467" height="319" alt="final dashboard" src="https://github.com/user-attachments/assets/515ae799-a99c-4a0a-b191-d016ad6682f1" />

**Note:** This project demonstrates practical application of data science techniques to derive clear, actionable business strategy from complex raw data.
