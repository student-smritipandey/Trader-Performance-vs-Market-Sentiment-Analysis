# Trader Performance vs Market Sentiment Analysis

📌 Project Overview

**This project explores the relationship between trader performance and market sentiment.
The objective is to uncover hidden patterns and generate insights that can help design smarter trading strategies.**

The analysis combines trading data (PnL, trading volume, fees, trader activity) with sentiment data (Fear/ Neutral/ Greed/ Extreme greed/ Extreme fear classifications).

📁 Dataset 

**Historical data** - https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

**Fear greed data** - https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

 

🔍 Key Objectives

Explore how market sentiment affects trader performance.

Compare PnL across sentiment types (Fear/ Neutral/ Greed/ Extreme greed/ Extreme fear classifications).

Check for lag effects (does yesterday’s sentiment impact today’s PnL?).

Identify which traders are more sensitive to market sentiment.

Understand how fees and trading volume behave under different sentiment conditions.

⚙️ Tools & Libraries

Python (Pandas, NumPy) – Data wrangling & preprocessing

Matplotlib / Seaborn – Data visualization

Plotly – Interactive charts

Scikit-learn – Clustering (KMeans), standardization

📂 Workflow
1. Data Preparation

Convert timestamps into daily dates

Aggregate trader performance per day (PnL, Size, fees, active accounts)

Merge trader performance with sentiment data

2. Exploratory Data Analysis

Correlations between PnL and sentiment values

Average PnL grouped by sentiment class

Lag analysis (sentiment vs next-day PnL)

3. Insights Extraction

Which sentiment classes correspond to higher/lower PnL

Which traders are most/least impacted by sentiment

How volume and fees move with sentiment

4. Visualization

📈 PnL vs Sentiment time series

🔵 Scatter plots (PnL vs sentiment values)

📊 Bar charts (Avg PnL by sentiment class)

🎨 Heatmaps (correlation matrix)

🟢 Clusters of trading days (using KMeans)

📊 Example Insights

Positive sentiment days often correspond to higher average PnL.

Some traders show strong correlation with sentiment, while others are relatively unaffected.

Fees tend to increase with trading volume, but not always with higher profits.

Yesterday’s sentiment can sometimes predict today’s performance → potential trading signal.


🎯 Business Value

Helps traders understand when to scale up or reduce exposure based on sentiment.

Provides risk management insights for negative sentiment regimes.

Identifies top traders who benefit most from sentiment trends.

Suggests how volume/fees efficiency can be improved.

👩‍💻 Author

Smriti Pandey
📍 B.Tech CSE (AIML) | GTBIT
