# Predicting the Football Market 

# About

This is a Mini-Project for SC5010 (Introduction to Data Analysis) which focuses on football players' statistics scraped from [Fotmob](https://www.fotmob.com/).

# Problem Definition

- Use regression models to predict a football player's market value based on their season statistics
- Determine which is the best model in predicting market value

# Data Collection

Player data from the past 2 seasons (2020-2021 and 2021-2022) were collected using our self-designed web scraper. The details can be found in [here]().

# Models Used

- Linear Regression
- Linear Regression (with higher order terms)
- Ridge Regression
- Lasso Regression
- Random Forest Regression

# Results

| Model 					                         |     R2 Score 		       |  MSE                 |
|-----------------------------------------:|------------------------:|---------------------:|
| Linear Regression 			                 |     0.6124299824151251  | 146.45024016416988.  |
| Linear Regression (higher order terms) 	 |     0.6431267219862531  | 144.95331830442498.  |
| Ridge Regression 			                   |     0.6448971342819805  | 134.5894783980847.   |
| Lasso Regression 			                   |     0.640337661964369 	 | 123.10347326169641.  |
| Random Forest Regression 		             |     0.6063040966499413  | 147.7985546636136.   |


# Takeaways

- Web scraping
- Ridge and Lasso Regression
- Hyperparameter Tuning (value of alpha)
- Cross Validation

# References

- https://www.fotmob.com/
- https://realpython.com/beautiful-soup-web-scraper-python/
- https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/
- https://towardsdatascience.com/random-forest-regression-5f605132d19d