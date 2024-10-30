# Video Game

## Project Objective

This project analyzes Video Game sales over the decades. Using Tableau for visualization, we will explore peak sales periods and the platforms that the publishers released their games on and distribution of sales across regions during those periods.


## Objectives

The primary objectives of this project are:

1. Analyze Sales Trends:
   - Identify peak periods for video game sales.
   - Investigate factors influencing sales peaks, including platform performance and regional market dynamics.

2. Compare Platform Performance:
   - Analyze best-selling platforms over the decades, highlighting trends in platform popularity.
   - Compare sales performance of top platforms during peak periods to overall historical sales data.

3. Examine Regional Sales Distribution:
   - Assess sales distribution by region to understand market dynamics in different geographical areas.
   - Identify key publishers and their contributions to sales in various regions during peak periods.

## Repository Structure

**Dataset**
- Original csv file 1) video-games-developers.csv, containing data on developers, cities, countries  
- Original csv file 2) vgsales.csv, containing data on video games, platforms, sales number
- Updated csv file: videogame.csv, combing two original dataset so that each game has a platform, publisher and country

**Preprocessing** (VideoGame.ipynb)
- Contains a Python notebook that merge, clean, and perform EDA on the datasets

**Visualization** (VideoGame.twb)
- Contains a Tableau workbook file featuring visualizations, a dashboard, and a data story that analyzes the sales data over the years
  
## Data Preprocessing 

The data were merged and cleaned, dropping null values so that each game row had corresponding columns such as Platform, Sales, Publisher, Country and Year. 

## Tableau Visualizations

Visit the [Tableau Dashboard](https://public.tableau.com/app/profile/melody.feng/viz/VideoGame_17298987144570/PeakPeriodFactors) to explore the visualizations and insights.

## Key Questions and Insights

What were the peak periods for video game sales and which platforms were used?

Analysis: I analyzed the leading platforms throughout the years and compared them to the top platforms during the peak period of 2008 - 2009. Additionally, I examined sales by region and publisher distribution to platforms during peak periods.

Visualization: Dashboard made of visualizations including: Top Overall Selling Platforms (Table), Total Sales by Platform (Bar Chart), Distribution of Sales Over the Years (Line Chart), Publisher Distribution of Top Platforms (Highlight Table)

Insight: Overall video game sales peaked around 2008 and 2009, with Wii being the peak platform for video game at the time. The PS2, which remains the overall top global-selling platform, reached its peak in the early 2000s. During these peak periods, the United States held the largest market share among sales, with Japan as the leading publisher, Nintendo releasing the most games on Wii. 

<img width="978" alt="Screenshot 2024-10-25 at 7 07 06 PM" src="https://github.com/user-attachments/assets/d4ae6f6c-6d0b-4710-9247-1b516ee38fdc">

## Conclusion and Recomendations 

Based on the insights from this analysis, as a publisher in the video game industry, it is valuable to consider:

**1. Diversify Platform Offerings:** Invest in developing games for platforms that continue to show strong sales, such as the PSP, while also exploring emerging platforms to capture new audiences. Given that platforms typically experience rapid popularity and subsequent decline, diversifying offerings can mitigate risks and enhance market reach.

**2. Target Key Regions:** Tailor marketing efforts to regions with the highest sales, such as the United States and Japan, ensuring that strategies resonate with local gaming communities.

3. **Monitor Industry Trends:** Continuously analyze sales data and emerging trends to quickly adapt strategies, ensuring releases align with consumer interests and platform performance. This involves tracking shifts in gaming preferences, such as the rise of mobile gaming and popular genres, and adjusting marketing and development efforts accordingly.

## Dataset

The dataset used in this analysis was comprised of dataset that contains information about video games publishers and dataset of video games with sales greater than 100,000 copies scraped from vgchartz.com. 

### Key Attributes:

- **Video Game Data:** Name, Rank, Genre, Year, Platform
- **Sales Data:** NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales
- **Publisher Data:** Publisher, Country

This project uses [video games sales data](https://www.kaggle.com/datasets/gregorut/videogamesales) and [video games developers data ](https://www.kaggle.com/datasets/andreshg/videogamescompaniesregions?select=video-games-developers.csv) sourced from Kaggle.
