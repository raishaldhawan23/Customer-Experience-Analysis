# Customer-Experience-Analysis

Enhancing Customer Experience Through Sentiment Analysis and Feedback Insights

## Executive Summary
This project focuses on analyzing customer feedback to uncover actionable insights that can enhance the user experience for a company. By leveraging Python and Jupyter Notebook, the project employs sentiment analysis, topic modeling, and visualization techniques to identify strengths, pain points, and areas for improvement. The goal is to provide data-driven recommendations that help improve customer satisfaction, loyalty, and overall brand perception.
The project includes a detailed analysis of customer reviews, sentiment distribution, and key themes, along with the calculation of the Net Promoter Score (NPS). The insights generated are aimed at assisting companies in optimizing their customer experience strategies.

## Project Structure
- uber_reviews_without_reviewid.csv: Contains customer feedback data, including review scores, text reviews, and sentiment categories.
- Customer_Experience_Analysis.ipynb: The primary Jupyter Notebook file containing the Python code for data analysis, sentiment analysis, and visualization.
- README.md: This document provides an overview of the project, repository structure, and instructions for running the analysis.

## Project Goals
- Understand Customer Sentiment: Analyze the distribution of positive, neutral, and negative reviews to identify overall customer satisfaction levels.
- Identify Key Themes: Use topic modeling to uncover recurring themes in customer feedback, such as service quality, app functionality, and pricing concerns.
- Calculate NPS: Determine the Net Promoter Score to measure customer loyalty and identify areas for improvement.
- Provide Actionable Recommendations: Offer data-driven strategies to address pain points and enhance customer experience.

## Getting Started
To run this project, install the necessary Python libraries:

<pre>import pandas as pd
import numpy as np
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
import matplotlib.pyplot as plt
import seaborn as sns
</pre>

## Methodology
- Data Collection and Cleaning: Sourced customer feedback data, including review scores and text reviews. Cleaned and preprocessed the data to ensure consistency and readiness for analysis.
- Sentiment Analysis: Analyzed the sentiment distribution of reviews to understand overall customer satisfaction, and identified strong positive and negative sentiments to pinpoint critical pain points.
- Word Cloud Generation and Topic Modeling: Identified the most common pain points and strengths. Generated word clouds to visualize frequently mentioned terms in positive and negative reviews.
- NPS Calculation: Calculated the Net Promoter Score (NPS) to measure customer loyalty and identify promoters, passives, and detractors.
- Visualization: Created visualizations such as bar charts, pie charts, and word clouds to present insights effectively.

## Key Visualizations
- Sentiment Distribution: A bar chart showing the distribution of positive, neutral, and negative reviews.
- Word Clouds: Visualizations of frequently mentioned words in positive and negative reviews.
- Topic Modeling Results: A table summarizing key themes and their associated keywords.
- NPS Score: A metric showing the Net Promoter Score and its implications for customer loyalty.

## Conclusion
This project successfully analyzes customer feedback to provide actionable insights for improving customer experience. By leveraging sentiment analysis, topic modeling, and NPS calculation, the project equips companies with data-driven strategies to enhance customer satisfaction and loyalty.
