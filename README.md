# 🎬Movies Data Analysis & Recommendation Project
This repository is an end-to-end data science journey using a movies dataset from Kaggle.
From Exploratory Data Analysis to Recommendation Systems, this project combines data wrangling, visualization, machine learning, and market insights into one comprehensive analysis.

### 📊 Dataset: [Movies Dataset on Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies?select=movies.csv)
Contains: name, rating, genre, year, score, votes, director, writer, star, country, budget, gross, company, runtime.

## 🔍 Project Pipeline
1. Exploratory Data Analysis (EDA) → [1_EDA.ipynb](https://github.com/Lubula/Movies-Data-Analysis/blob/main/1_EDA.ipynb)
- Cleaned missing & inconsistent values.
- Explored distribution of ratings, budgets, revenues, and genres
- Visualized trends in gross revenue over decades.
- Detected outliers using boxplots & scatterplots.
### 📹 Video Tutorial: [YouTube EDA Walkthrough](https://youtu.be/-bxzgyFF6a4)

2. Predictive Modeling – Box Office Success → [2_Box_Office_success_Predictive_Model.ipynb](https://github.com/Lubula/Movies-Data-Analysis/blob/main/2_Box_Office_success_Predictive_Model.ipynb)
- Applied regression techniques (Linear Regression, Random Forest).
- Engineered features like ROI, Budget_Category, and Director_Success.
- Achieved R² score of X.XX in predicting box office gross.

3. Genre Classification → [3_Genre_Classification.ipynb](https://github.com/Lubula/Movies-Data-Analysis/blob/main/3_Genre_Classification.ipynb)
- Multi-class classification using logistic regression & TF-IDF.
- Built a genre prediction model with XX% accuracy.
  
4. Recommendation System → [4_Recommendation_System.ipynb](https://github.com/Lubula/Movies-Data-Analysis/blob/main/4_Recommendation_System.ipynb)
- Used cosine similarity on combined features (director, star, genre).
- Returns top N similar movies based on user input.
### 📹 Video Tutorial: [Recommendation System Walkthrough](https://youtu.be/_pzOoKjbROs)

5. Time Series Forecasting → [5_Time_series_Forecasting_&_Analysis.ipynb](https://github.com/Lubula/Movies-Data-Analysis/blob/main/5_Time_series_Forecasting_%26_Analysis.ipynb)
- Analyzed trends in movie releases over the years.
- Built ARIMA model to forecast future release patterns.

6. Market Basket Analysis → [6_Market_Basket_Analysis.ipynb](https://github.com/Lubula/Movies-Data-Analysis/blob/main/6_Market_Basket_Analysis.ipynb)
- Applied Apriori Algorithm to identify common movie genre combinations.
- Example: “Action + Adventure” appears together X% of the time.

## 📺 Tutorials & Resources
- EDA Video: [Watch on YouTube](https://youtu.be/-bxzgyFF6a4)
- Movies Recommendation Model Video: [Watch on YouTube](https://youtu.be/_pzOoKjbROs)
