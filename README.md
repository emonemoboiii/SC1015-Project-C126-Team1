# SC1015-Project-C126-Team1
Predicting the Worldwide Gross Revenue for Hollywood Movies using Data Science

# About The Project
This is a project for SC1015 - Intro to Data Science and AI) which focuses on the analysis on the Worldwide Revenue of HollyWood Movies predictor. For the entire walkthrough of the project, please view the notebooks/readmes in this order:
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis and Visaulization
4. Model Building 

# Problem Definition
- How different numeric variables of making a movie affects the worldwide revenue generated by the movie.
- Whether the categorical variables also affect the worldwide revenue generated by the movie.

# Model Used
1. Regression
2. Random Tree
3. XGBoost Regression

# Key Takeaways from our primary EDA
1. Number of Outliers
- Production Cost has 10 outliers.
- Worldwide Gross has 17 outliers.
- Runtime has 5 outliers.

2. Skewness of Data
- Production Cost has sknewness of 0.706946
- Worldwide Gross has sknewness of 0.873779
- Runtime has sknewness of 0.3821170
  
3. Correlation of Data
- Between the 2 variables (production cost & runtime), production cost has a higher correlation value of 0.49
  
4. Two Categorical datas were used for our analysis
- Genre
- MPAA Rating (in terms of appropriateness of movie)

5. RMSE & MSE Value
  a. For Production Cost vs Worldwide Gross
    - Mean Squared Error (MSE): 6.925547305890477e+16
    - Root Mean Squared Error (RMSE): 263164346.1012619 
    
  b. For Runtime vs Worldwide Gross
    - Mean Squared Error (MSE): 6.149849345212966e+16
    - Root Mean Squared Error (RMSE): 247988897.84046718

# Conclusion



# Contributors
- @emonemoboiii (Tony Evans Adisurya) - Data Cleaning, EDA and Visualisation
- @valentinotok (Tok Valentino) - Data Cleaning, EDA and Visualisation

# References
