# Jyszelle Martinez – Data Analytics Portfolio

Welcome! This portfolio highlights key analytics and machine learning projects I've completed, using tools like Python, SQL, Tableau, and cloud services like AWS EMR. Each project includes practical applications of data cleaning, modeling, visualization, and AI.

## IMDb Rating Forecasting
**Tools:** PySpark, AWS EMR, Random Forest  
-	Predicted IMDb ratings with R² = 0.90 using a Random Forest model in PySpark trained on metadata from 206K+ U.S. films.
-	Engineered features for actor/director experience using IMDb-weighted formulas and analyzed trends across genre, decade, and runtime.
-	Tuned model via cross-validation and grid search, and visualized performance using Seaborn & Matplotlib.
-	Built an interactive prediction function for unseen movies and processed large-scale data using AWS EMR, S3, and Docker.
-	[View Notebook](./imdb_rating_forecast.ipynb)

## Mental Illness Detection Using NLP  
**Tools:** Python, Transformers, RoBERTa, LIME  
-	Fine-tuned transformer models (BERT, DistilBERT, RoBERTa) on 6-class Reddit dataset (~6,000 samples) to detect stress, depression, anxiety, and related conditions.
-	Achieved F1 score of 0.73 and accuracy of 74.8% using RoBERTa with optimized hyperparameters (batch size, learning rate, epochs).
-	Applied LIME for model interpretability and explainability.
-	Demonstrated real-world potential for early mental health screening based on social media text.
-	[View Notebook](./mental_health_nlp.ipynb)

## HR Attrition Prediction – Primoris Energy
**Tools:** Python, Logistic Regression, Random Forest, Tableau  
-	Developed Random Forest and Logistic Regression models on data from 12,000+ employees to predict voluntary vs. involuntary terminations.
-	Engineered 70+ features (e.g., promotion frequency, tenure gaps, rehire patterns) and identified key risk factors like project assignment and length of stay.
-	Built an interactive Tableau dashboard for HR to monitor at-risk employees and drive retention strategies.

## Dual Eligibility Forecast – Wellmark Case Competition
**Tools:** Python, Tableau, Macroeconomic Data 
-	Built dual eligibility forecasts using demographic, economic, and policy data; projected Medicaid-Medicare demand through 2035 using Tableau and Python.
-	Identified key drivers of eligibility growth post-COVID, including inflation, CPI: Medical Care, and legislative policy shifts at state and federal levels.
-	Recommended strategies for provider workforce expansion and rural infrastructure investment based on county-level trends and population projections.

## Retail Revenue Analysis – Rudi’s Bakery
**Tools:** Python, Tableau, Clustering, Regression  
-	Cleaned and standardized 60K+ rows of retail data using Python and regex.
-	Built Tableau dashboards and regression models to uncover revenue drivers by store and city.
-	Identified Costco and Whole Foods as top-performing retailers, found education level to be the strongest predictor of store performance via clustering and regression.
-	Detected anomalies using Isolation Forest and delivered SKU-level return analysis and product recommendations to optimize inventory and reduce costs.












