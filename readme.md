# ANALYZING USER ATTITUDE AND SATISFACTION TOWARD KBZ PAY MOBILE APPLICATION USING SECONDARY ONLINE REVIEW DATA


This repository contains the data, source code, and analysis for my MSc thesis at GISMA University of Applied Sciences. The study investigates user attitudes toward the KBZ Pay mobile application using 1,500 reviews from the Google Play Store.

## 📋 Project Overview
- **Objective:** To identify key factors influencing user ratings and sentiment.
- **Methodology:** Sentiment Analysis (TextBlob), Descriptive Statistics, and Predictive Modeling (Random Forest Regressor).
- **Tools:** Python (Pandas, Matplotlib, Seaborn, Scikit-learn).

## 📁 Repository Structure

### 1. Data (`/dataset`)
- `KBZ_Pay.csv`: Original dataset of KBZ Pay reviews from Google Play Store.
- `KBZ_Pay_Translated_with_Sentiment.csv`: Reviews translated to English with sentiment analysis applied.
- `KBZ_Pay_Fully_Processed_Data.csv`: Fully preprocessed data with all features cleaned.
- `KBZ_Pay_Final_Correlation_Data_Ver2.csv`: Final dataset prepared for correlation and predictive analysis.
- `KBZ_Pay_Sentiment_Cate_Ver3.csv`: The final cleaned dataset includi

### 2. Analysis Notebooks (`/dataset`)
- `data_preprocessing.ipynb`: Data cleaning and preprocessing pipeline.
- `Device Type Charts.ipynb`: Generates charts for device type analysis (Phone vs. Tablet).
- `lang n rating.ipynb`: Language analysis and rating distribution.
- `Sentiment Category for ver 3.ipynb`: Sentiment categorization and encoding.
- `Pearson Correlation.ipynb`: Pearson correlation analysis between variables.
- `Pearson Correlation with Emoji ver 2.ipynb`: Correlation analysis including emoji count features.
- `Random Froest Regressor.ipynb`: Predictive modeling using Random Forest Regressor for feature importance.

### 3. Visualizations (`/dataset`)
- `sentiment_distribution_pie_chart.png`: Distribution of sentiment categories.
- `language_distribution_pie_chart.png`: Distribution of review languages.
- `average_rating_by_language_bar_chart.png`: Average ratings by language.
- `average_rating_by_sentiment_bar_chart.png`: Average ratings by sentiment category.

## 🚀 How to Run the Analysis

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/tayzarnaung/GISMA-KBZ-Pay-Satisfaction.git](https://github.com/tayzarnaung/GISMA-KBZ-Pay-Satisfaction.git)