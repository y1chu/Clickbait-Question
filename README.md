# COGS 108 - Clickbait Youtube Titles and User Engagement

## Overview
This project explores the correlation between clickbait titles on YouTube and user engagement, specifically focusing on likes, views, and comments. Preliminary findings indicate a significant correlation between clickbait techniques, such as titles in all caps, and higher user engagement metrics.

## Table of Contents
1. [Hypothesis](#hypothesis)
2. [Data Sources](#data-sources)
3. [Analysis & Results](#analysis--results)
4. [Conclusions](#conclusions)

## Hypothesis
Based on observed trends, we hypothesize that videos with clickbait titles receive higher views, likes, and dislikes than non-clickbait titles. Clickbait titles, by sparking curiosity or eliciting emotional responses, likely lead to increased video interactions.

## Data Sources
- **Dataset:** US_youtube_trending_data.csv
- **Location:** [Kaggle Dataset](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?resource=download)
- **Dimensions:** 201,189 rows x 16 columns
- **Description:** Aggregates several months of YouTube video data, including titles, likes, dislikes, comments, and more.

## Analysis & Results
Key steps in the analysis include:
- Descriptive statistics for numerical variables.
- Correlation matrix to identify relationships between metrics.
- Analysis of title capitalization and its potential influence on video popularity.

Preliminary results suggest:
- A perfect correlation between view_count and total_engagement.
- Strong positive correlations between likes and both view_count and total_engagement.
- Caps percentages in titles seem to influence video popularity.

## Conclusions
Clickbait titles, especially those employing capitalization techniques, appear to have a positive effect on user engagement on YouTube. While these findings do highlight the effectiveness of clickbait, it's also observed that higher engagement doesn't always equate to uniformly positive feedback, as seen from increased dislikes and comments.

## How to Run the Notebook
1. Ensure you have all required libraries: pandas, numpy, seaborn, matplotlib.
2. Download the dataset from the provided Kaggle link.
3. Open and run `main.ipynb`.

**Note:** Always ensure data paths are set correctly when working in a different environment.
