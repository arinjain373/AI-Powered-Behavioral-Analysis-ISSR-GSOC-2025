# Crisis-Related Social Media Analysis

This project focuses on analyzing crisis-related discussions on social media, particularly Reddit, to identify mental health distress, substance use, and suicidality. The analysis involves text preprocessing, sentiment analysis, crisis term detection, risk level categorization, geocoding, and visualization.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)


## Project Overview
The project consists of three main tasks:
1. **Extracting and Preprocessing Reddit Posts** - Collecting crisis-related posts using specific keywords, storing them in CSV/JSON format, and cleaning the text for NLP tasks.
2. **Sentiment Analysis & Crisis Classification** - Analyzing sentiment with TextBlob, detecting crisis-related terms using TF-IDF, and categorizing posts into risk levels (High, Moderate, Low).
3. **Geocoding and Visualization** - Extracting location metadata or using NLP-based place recognition to visualize crisis-related discussions on a heatmap using Folium or Plotly.

## Features
- **Data Extraction**: Fetching social media data using Reddit APIs.
- **Text Preprocessing**: Tokenization, stopword removal, stemming, and lemmatization.
- **Sentiment Analysis**: Using TextBlob to analyze sentiment polarity.
- **Crisis Term Detection**: TF-IDF-based identification of key crisis-related terms.
- **Risk Categorization**: Classifying posts into High, Moderate, or Low risk based on sentiment and keywords.
- **Geolocation Mapping**: Extracting location information and visualizing crisis hotspots.

##  Dataset
- The dataset consists of Reddit posts retrieved using crisis-related keywords.
- Preprocessed text is stored in structured formats (CSV).
- Annotations include sentiment scores and risk levels.

## Methodology
- **Data Collection**: Extract posts using Reddit's API with predefined keywords.
- **Text Processing**: Tokenization, removal of noise, stopword filtering.
- **Sentiment Analysis**: Compute sentiment polarity with TextBlob.
- **Crisis Detection**: Use TF-IDF to highlight crisis-related terms.
- **Risk Classification**: Categorize posts based on sentiment and keywords.
- **Geolocation & Visualization**: Extract location data and plot heatmaps.

## Results
- Identification of high-risk posts for crisis intervention.
- Visualization of crisis hotspots.
- Insights into sentiment distribution across social media.


