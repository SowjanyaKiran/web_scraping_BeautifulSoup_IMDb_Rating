# 🎬 IMDb Top 250 Movies Analysis & Prediction#

**📌 Overview**

This project scrapes, cleans, and analyzes the IMDb Top 250 Movies dataset.
Using machine learning models, it attempts to predict IMDb ratings based on features such as duration, year, votes, and genres.

It also includes exploratory data analysis (EDA) with visualizations and correlation analysis.

**🚀 Features**

✅ Web Scraping – Extracted IMDb Top 250 movies (title, genre, rating, votes, duration, etc.)

✅ Data Cleaning – Fixed missing values, parsed duration (ISO 8601 → minutes), extracted year, processed genres

✅ EDA – Correlation matrix, distribution plots, genre-wise analysis

✅ Feature Engineering – One-hot encoding for genres, numeric transformations

✅ Modeling – Trained and evaluated multiple regression models:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

✅ Hyperparameter Tuning with GridSearchCV
✅ Model Comparison – R² score, MAE, RMSE

**🛠️ Tech Stack**

Language: Python 🐍
Libraries:
requests, BeautifulSoup → Web scraping
pandas, numpy → Data processing
matplotlib, seaborn → Visualization
scikit-learn → Machine Learning

**📊 Results**

Best model: Random Forest / Gradient Boosting (after tuning)

Achieved R² ≈ 0.25 – 0.35 → Ratings are difficult to predict from limited features.

Strongest predictor: Number of votes (popularity).

Duration & genre had weak correlation with IMDb rating.

**📂 Project Structure**
├── imdb_analysis.ipynb   # Jupyter notebook with code
├── imdb_data.csv         # Cleaned dataset
├── README.md             # Project documentation

**🔮 Future Improvements**

Add text analysis from movie titles/descriptions using NLP.

Include director & cast features.

Use advanced models: XGBoost, CatBoost, Deep Learning.

Deploy model with Flask/Streamlit for live predictions.

**👨‍💻 Author**

Developed by Sowjanya U ✨
If you like this repo, ⭐ it and connect with me!
