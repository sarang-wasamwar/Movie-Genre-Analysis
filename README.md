# 🎬 Movie Genre Analysis using R

A statistical data analysis project that explores movie trends, ratings, revenue, profitability, and genre-based insights using the R programming language.

---

## 📌 Project Overview

This project analyzes movie datasets based on genres using statistical techniques and data visualization in R. The goal is to discover patterns between movie attributes such as:

- Runtime
- Ratings
- Budget
- Revenue
- Popularity
- ROI (Return on Investment)
- Genres
- Production Companies

The project also applies Machine Learning using Random Forest Regression to predict movie ratings.

---

## 👨‍💻 Team Members

- Sarang Wasamwar
- Ayush Thakare [GitHub Link: ]
- Shubham Navale [GitHub Link: ]

---

## 🤝 Contributors

This project was collaboratively developed by:

| Contributor | Contribution |
|-------------|--------------|
| Sarang Wasamwar | Data Analysis, Visualization, Documentation |
| Ayush Thakare | Data Cleaning, EDA, Statistical Analysis |
| Shubham Navale | Machine Learning Model, Presentation |

---

## 📂 Dataset Information

Dataset Source:  
[Kaggle](https://www.kaggle.com/)

### Dataset Features

#### Quantitative Variables
- Budget
- Revenue
- Runtime
- Popularity
- Vote Count
- Vote Average
- Profit
- ROI

#### Categorical Variables
- Genres
- Production Companies
- Director
- Cast

#### Date Variables
- Release Date
- Release Year

---

## 🛠️ Technologies & Libraries Used

### Programming Language
- R

### Libraries
- tidyverse
- dplyr
- ggplot2
- plotly
- lubridate
- readr
- randomForest

---

## 🔍 Methodology

### 1. Data Collection
Imported the movie dataset into R for analysis.

### 2. Data Cleaning
- Removed missing values
- Removed duplicate records
- Converted date formats
- Created derived fields:
  - `profit = revenue - budget`
  - `ROI = revenue / budget`

### 3. Exploratory Data Analysis (EDA)
Performed statistical analysis and identified trends using visualization techniques.

### 4. Visualization
Used:
- Scatter Plots
- Bar Charts
- Boxplots
- Correlation Analysis

### 5. Machine Learning
Applied Random Forest Regression to predict movie ratings.

---

# 📊 Problem Statements & Insights

## PS1: Relationship Between Runtime and Ratings

### Observation
- Weak positive correlation between runtime and ratings
- Longer movies slightly tend to receive better ratings

### Conclusion
Runtime alone is not a strong predictor of audience preference.

---

## PS2: Runtime & Ratings by Genre

### Observation
- Adventure, Action, Fantasy, and Sci-Fi genres receive higher ratings
- Genre influences ratings more than runtime

### Conclusion
Storytelling and audience preference matter more than duration.

---

## PS3: Highest Return on Investment (ROI)

### Observation
- Star Wars and Avatar showed very high ROI
- Popularity does not always indicate profitability

### Conclusion
Smart budgeting and audience appeal drive ROI.

---

## PS4: Budget vs Revenue

### Observation
- Higher budgets generally generate higher revenue
- Some low-budget films outperform expectations

### Conclusion
Budget helps but does not guarantee success.

---

## PS5: Top Production Companies

### Observation
- Top companies dominate revenue and movie count

### Conclusion
Large production houses lead the industry through consistent success.

---

## PS6: Popularity & Vote Count Outliers

### Observation
- Some movies show unusually high popularity or votes

### Conclusion
Audience behavior varies significantly across movies.

---

## PS7: Movie Releases Over Time

### Observation
- Movie production increased rapidly after the 1990s

### Conclusion
Streaming platforms and digital technology boosted production growth.

---

## PS8: Genre vs Average Revenue

### Observation
- Adventure, Fantasy, and Animation genres generate highest revenue

### Conclusion
Family-friendly blockbuster genres are financially stronger.

---

## PS9: Genre Popularity

### Observation
- Drama is the most produced genre

### Conclusion
Drama remains the dominant genre in the movie industry.

---

## PS10: Linear Regression Analysis

### Observation
- Strong positive correlation between budget and revenue
- Correlation coefficient ≈ 0.73

### Conclusion
Budget significantly influences movie revenue.

---

# 🤖 Machine Learning Model

## PS11: Movie Rating Prediction using Random Forest

### Features Used
- Budget
- Revenue
- Runtime
- Genre
- Vote Count
- Popularity

### Model Performance
- Strong R² score
- Low RMSE
- High prediction accuracy

### Key Predictors
- Popularity
- Vote Count
- Revenue

### Example Prediction

Predicted Rating: **6.48 / 10**

For a movie with:
- Budget: 120 Million
- Revenue: 400 Million
- Runtime: 130 Minutes
- Genre: Action
- Vote Count: 2500
- Popularity: 60

---

# 📈 Key Learnings

- Data preprocessing is essential for accurate analysis
- Genre strongly impacts ratings and revenue
- Higher budgets often improve revenue potential
- Machine Learning can effectively predict movie ratings

---

# 🚀 Future Improvements

- Deploy as an interactive dashboard
- Add sentiment analysis using movie reviews
- Use Deep Learning models for prediction
- Integrate live movie datasets via APIs

---

# 📷 Sample Visualizations

- Scatter Plot: Runtime vs Ratings
- Budget vs Revenue Regression Plot
- Genre Revenue Analysis
- Popularity vs Vote Count Analysis

---

# 📜 License

This project is for academic and educational purposes.

---

# 🙌 Acknowledgement

Special thanks to **Dr. Shaziya Shaikh** for guidance and support throughout the project.

---

# ⭐ GitHub

If you like this project, give it a ⭐ on GitHub!
