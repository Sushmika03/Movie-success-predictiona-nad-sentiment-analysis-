# Movie Success Prediction and Sentiment Study

This project aims to predict the box office success of movies using features such as budget, vote average, and sentiment of movie overviews. It combines data analysis, natural language processing (NLP), and machine learning.

## Objective

- Predict movie revenue based on available data.
- Analyze sentiment from movie overviews using VADER.
- Build a regression model to evaluate prediction accuracy.

##  Dataset

The project uses the **TMDB 5000 Movie Dataset** from Kaggle:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

You can download it from:  
[TMDB Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)


## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (optional for visuals)
- Scikit-learn (Linear Regression)
- NLTK (VADER Sentiment Analysis)

## Project Workflow

The project is divided into three main parts:

### 1. Data Preprocessing
- Load and merge movie and credits datasets
- Clean missing or zero values
- Extract key features like `budget`, `vote_average`, `revenue`, and `overview`

### 2. Sentiment Analysis
- Use NLTK's VADER to analyze sentiment of movie overviews
- Add `sentiment_score` as a new feature for modeling

### 3. Predictive Modeling
- Use `LinearRegression` from Scikit-learn
- Train-test split on selected features
- Evaluate using Mean Squared Error and R² score


## Model Performance

- **Mean Squared Error**: ~2.53 × 10¹⁶  
- **R² Score**: ~0.50 (The model explains ~50% variance in revenue)


## Output

- Cleaned dataset with sentiment scores
- Regression predictions
- Performance metrics
- (Optional) Visuals showing sentiment trends or predictions


##  What I Learned

- Real-world data is often incomplete and messy
- How to work with textual data using NLP (VADER)
- Basics of regression modeling and evaluation metrics
- Importance of feature selection in machine learning



## Acknowledgements

- [Kaggle](https://www.kaggle.com/) for the dataset
- [NLTK](https://www.nltk.org/) for sentiment analysis tools
- Scikit-learn for the modeling framework



Feel free to explore, learn, and build on this project!

clicl the link below for the google colab notebook 
[https://colab.research.google.com/drive/1sB_BE-mMrZoqwEC29nSq47wAyYHRCSRh?usp=sharing]

the project report is also attached to this file 
