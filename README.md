📊 Netflix Data Analysis

📌 Project Overview

This project performs an exploratory data analysis (EDA) on the Netflix Movies & TV Shows dataset to uncover patterns in content distribution, growth trends, genres, ratings, and geographical reach.
The analysis focuses on cleaning real-world data, transforming multi-value columns, and generating insightful visualizations to understand Netflix’s content strategy over time.

🎯 Objectives

Clean and preprocess Netflix content data

Analyze how Netflix’s content library has evolved over the years

Understand distribution across Movies vs TV Shows

Explore genres, ratings, and countries

Extract meaningful insights using visual analytics

📂 Dataset Description

The dataset includes information about Netflix titles such as:

type (Movie / TV Show)

title

director

cast

country

date_added

release_year

rating

duration

listed_in (genres)

description

🧹 Data Cleaning & Preparation

Converted date_added to datetime format

Handled missing values by:

Replacing non-critical missing text values with "Unknown"

Removing rows with missing critical values like date_added or rating

Standardized text columns

Split multi-value columns (listed_in, country) and normalized them using explode()

Created derived features such as year of content addition

🔧 Feature Engineering

Extracted year from date_added for time-series analysis

Normalized genres and countries into individual rows

Prepared aggregated datasets for genre-wise, country-wise, and yearly analysis

📈 Exploratory Data Analysis

The analysis includes:

Distribution of Movies vs TV Shows

Year-wise content addition trends

Genre frequency analysis

Country-wise content contribution

Rating distribution and audience maturity analysis

Duration analysis for Movies and TV Shows

Visualizations were created using Matplotlib and Seaborn for clarity and readability.

🛠️ Tools & Technologies

Python

Pandas & NumPy – data manipulation

Matplotlib & Seaborn – visualization

Jupyter Notebook / Kaggle Notebook

🔑 Key Insights

Netflix’s content growth accelerated rapidly after 2015, peaking around 2019, indicating aggressive global expansion.

Movies dominate the platform, but TV Shows have shown steady and consistent growth over time.

International Movies and Dramas are the most prevalent genres, highlighting Netflix’s strong focus on global and diverse content.

🏁 Conclusion

This analysis reveals how Netflix evolved from a modest content library into a globally scaled streaming platform. The data shows a clear shift from gradual growth to aggressive expansion, followed by a recent phase of strategic consolidation. Netflix’s emphasis on international content, diverse genres, and mature audience ratings reflects its goal of catering to a wide global audience rather than a single market.

Overall, the project demonstrates how data cleaning, feature engineering, and visualization can transform raw data into meaningful business insights.

🚀 Future Improvements

Sentiment analysis on descriptions

Recommendation system based on genres and ratings

Deeper comparison between regional content strategies
