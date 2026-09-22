# Google Play Store App Performance & User Sentiment Analysis

## Project Overview

This project analyzes Google Play Store application data and user reviews to identify patterns related to app performance, popularity, pricing, ratings, and user sentiment.

The analysis combines data wrangling, exploratory data analysis, data visualization, and sentiment analysis to generate meaningful business insights and recommendations.

## Problem Statement

To analyze Google Play Store app data and user reviews to identify factors influencing app performance, popularity, and user satisfaction, and provide data-driven business insights for app improvement and monetization.

## Business Objective

To identify key factors affecting app popularity and user satisfaction, and use these insights to support data-driven decisions on app development, pricing, monetization, and user experience improvement.

## Datasets

The project uses two datasets:

### 1. Apps Dataset

Contains information about:
- App name
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

### 2. User Reviews Dataset

Contains:
- App
- Translated Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

## Data Cleaning & Preparation

The datasets were cleaned and prepared for analysis by:

- Identifying and removing duplicate records
- Analyzing and handling missing values
- Correcting a malformed record
- Validating app ratings within the expected 1–5 range
- Converting Reviews and Installs into numerical formats
- Converting Price into numerical values
- Standardizing app Size into MB
- Converting Last Updated into datetime format
- Removing completely empty review records
- Validating numerical ranges and data types

## Exploratory Data Analysis

The analysis examined:

- App category distribution
- Free vs Paid applications
- Rating distribution
- Paid app price distribution
- User sentiment distribution
- Reviews and installs
- App pricing trends
- App ratings across categories
- Sentiment polarity and subjectivity

## Data Visualization

The project includes Univariate, Bivariate, and Multivariate visualizations using:

- Bar charts
- Pie charts
- Histograms
- Box plots
- Line charts
- Scatter plots
- Pair plots
- Correlation heatmaps

These visualizations were used to identify patterns and relationships among app performance metrics and user feedback.

## Sentiment Analysis

User reviews were analyzed using:

- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

The analysis examined how user sentiment varies across apps and rating groups and helped identify potential areas of user satisfaction and dissatisfaction.

## Key Insights

- Free applications represent the majority of apps and generally have much higher average installs than paid applications.
- Reviews and installs show a positive relationship, indicating a connection between app reach and user engagement.
- App ratings are generally concentrated toward the higher end of the rating scale.
- User reviews contain a larger proportion of positive sentiment compared with negative and neutral sentiment.
- Sentiment varies across different app rating groups.
- App pricing and installs show varying patterns among paid applications.
- High ratings do not necessarily correspond to the highest number of installs.

## Business Recommendations

Based on the analysis, the client should:

- Focus on understanding high-demand app categories.
- Monitor ratings and negative reviews regularly.
- Use user feedback to identify areas for product improvement.
- Select appropriate Free or Paid monetization strategies.
- Consider installs, ratings, and market positioning when setting prices.
- Use sentiment analysis to continuously monitor user satisfaction.
- Make product and marketing decisions using multiple performance metrics rather than a single measure.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Project File

The complete analysis is available in:

`Google_playstore_app_analysis.ipynb`

## Conclusion

This project demonstrates how data wrangling, exploratory analysis, visualization, and sentiment analysis can transform raw Google Play Store data into meaningful business insights. The findings can support data-driven decisions related to app development, pricing, monetization, user satisfaction, and overall app performance.
