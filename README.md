# Global-Consumer-and-Market-Trend-Analysis-for-the-Video-Game-Industry
## Overview
The global video game industry is one of the most dynamic and profitable entertainment sectors. To remain competitive, it is essential to understand the factors influencing sales across regions, genres, platforms, and publishers. This project analyzes historical sales data (1980–2020) to identify key market trends, explore correlations with economic factors such as GDP, and uncover consumer behavior patterns based on reviews and ratings.

By combining **exploratory data analysis**, **visualization**, and **economic correlation studies**, the project provides actionable insights for developers, publishers, and stakeholders aiming to optimize strategies and expand into global markets.

## Goal
* Identify the most successful genres, platforms, and publishers over time.
* Explore regional sales trends across North America, Europe, and Japan.
* Investigate the relationship between GDP and video game sales.
* Analyze how consumer ratings (IGN, Steam) correlate with sales.
* Provide data-driven insights to support strategic decision-making.

## Methodology

* Dataset Selection
  * Video game sales dataset (Kaggle) https://www.kaggle.com/datasets/gregorut/videogamesales/data.
  * ESRB ratings (Kaggle) https://www.kaggle.com/datasets/imohtn/video-games-rating-by-esrb.
  * IGN scores dataset (Kaggle) https://www.kaggle.com/datasets/advancedforestry/ign-scores-dataset.
  * Steam review data (Reddit) https://www.reddit.com/r/gamedev/comments/x0qs4z/we_gathered_data_about_54000_games_in_steam_and/.
  * GDP per capita (World Bank DataBank) https://databank.worldbank.org/indicator/NY.GDP.PCAP.CD/1ff4a498/Popular-Indicators#

* Data Processing & EDA
  * Cleaned and merged multiple datasets
  * Conducted exploratory data analysis (EDA)
  * Applied correlation analysis between GDP and sales

* Visualization & Tools
  * R, ggplot2, dplyr, tidyverse, Plotly
  * Power BI dashboard for extended interactive analysis

## Results & Insights
### Market Trends
* **Global Sales**: Peaked in late 2000s (678.9M units), then declined due to market saturation and mobile/online competition.
* **Genres**: Action games surpassed sports as the dominant genre after 2010.
* **Platforms**: PS2, Xbox 360, and PS3 led global sales; Wii was strong in sports/family games.
* **Regional**: North America led in total sales, followed by Europe and Japan. Japan showed stable long-term performance despite GDP fluctuations.
* **Publishers**: Nintendo dominated global sales, followed by EA and Activision.

### Economic Correlation
* GDP vs Sales: Alignment before 2008 financial crisis; post-crisis, GDP recovered but sales lagged in NA/EU.
* Japan Exception: Sales remained stable despite GDP volatility, showing a resilient market.

### Consumer Behavior
* IGN Ratings: Sales generally higher above 7.5 IGN score, but diminishing returns beyond that threshold.
* Steam Reviews: Greater variability; some blockbuster games sold well despite mediocre Steam ratings (e.g., Call of Duty ~60%).

### Power BI Dashboard – Extended Analysis
<img width="787" height="600" alt="425963646-a58c0277-8bde-46c7-b912-253a19f7f8d9" src="https://github.com/user-attachments/assets/80eab939-77ef-4f04-b00e-60d3de1da54d" />

This interactive dashboard highlights:
* Global, regional, and genre-level sales performance.
* User-friendly filtering for exploring regions, publishers, and genres dynamically.

## Recommendation
* **For Developers**: Focus on action and sports genres to maximize broad audience reach.
* **For Publishers**: Leverage blockbuster strategies like Nintendo to dominate market share.
* **For Marketers**: Target North America and Europe for volume, but recognize Japan’s stability as a long-term market.
* **For Strategic Planning**: Use GDP correlations to anticipate market risks, but note the unique resilience of Japan’s gaming sector.
* **For Consumer Analytics**: Ratings matter, but marketing, timing, and brand identity can override review scores.




