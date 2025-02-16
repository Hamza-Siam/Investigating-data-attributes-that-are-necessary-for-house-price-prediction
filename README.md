# Investigating Data Attributes that are Necessary for House Price Prediction

* <h4><b> Overview </b></h4> 

  This project aims to develop a predictive model for forecasting house prices by analyzing a range of influential factors, including property features like the number of rooms, location, and the age of the house, as well as socio-economic attributes such as median income and proximity to key amenities. By leveraging multiple regression techniques, the objective is to identify and quantify the key drivers of housing prices, assess their impact, and build a robust model capable of providing accurate predictions. The model’s performance will be evaluated using key metrics, such as RMSE and R-squared, to ensure its reliability and utility for real-world applications in real estate markets.
  
* <h4><b> Key Findings </b></h4> 

  - <b> Significant Predictors of House Prices: </b> Key features like the number of rooms, proximity to major highways, and median income are found to have the highest correlation with house prices, indicating their critical role in pricing prediction.
  - <b> Multicollinearity Among Features: </b> Some features, such as the age of the house and the number of rooms, were found to be highly correlated with each other, which could affect the stability of regression models.
  - <b> Model Evaluation: </b> The regression model's performance was assessed using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), providing a clear measure of prediction accuracy and indicating areas for improvement.
  - <b> Impact of Location: </b> Geographic location (e.g., proximity to the city center) was shown to significantly influence house prices, with properties in urban areas commanding higher prices than those in rural areas.
  - <b> Influence of Socio-economic Factors: </b> Variables such as median income and school district ratings proved to be important factors in determining house values, emphasizing the socio-economic aspects of housing demand.
 
* <h4><b> Insightful Details </b></h4> 

  - <b> Correlation with Key Variables – </b> The analysis revealed that variables such as the number of rooms and the proximity to key amenities (e.g., schools and shops) were among the most influential predictors of house prices, offering valuable insights for future property investments.
  - <b> Impact of Age of Property – </b> Older properties tended to have lower prices on average compared to newer builds, with the condition of the property also playing a significant role in determining its market value.
  - <b> Model Performance Insights – </b> Linear regression demonstrated solid baseline performance, but more complex models such as Ridge and Lasso regression further enhanced prediction accuracy, highlighting the value of regularization in preventing overfitting.
  - <b> Feature Transformation Impact – </b> Transformation of skewed features, such as applying log transformations to skewed variables (e.g., house size), significantly improved model performance, demonstrating the importance of data preprocessing.
  - <b> Predictive Trends – </b> The model's predictive results showed consistent trends, such as a noticeable increase in house prices correlated with higher median household income and more developed neighborhood infrastructure. This insight could inform pricing strategies in real estate markets.

* <h4><b> Challenges </b></h4> 
 
  - <b> Data Quality Issues – </b> Missing or incomplete data for key features like location and property conditions required extensive data cleaning and imputation, which introduced potential bias and uncertainty in some predictions.
  - <b> Feature Selection – </b> Identifying the most relevant features for the predictive model was challenging, as some variables had minimal influence on the results, leading to iterative testing and refinement of feature selection methods.
  - <b> Model Overfitting – </b> Some models, particularly linear regression, struggled with overfitting to the training data, which resulted in less accurate predictions when applied to new or unseen data, necessitating the use of regularization techniques like Ridge and Lasso.
  - <b> Multicollinearity – </b> The presence of highly correlated features, such as the number of rooms and the house's square footage, created multicollinearity, which undermined model stability and the interpretability of certain coefficients.
  - <b> Computational Complexity – </b> As the dataset size grew and more complex models were implemented, the computational load increased, leading to longer training times and a need for optimization in the code to maintain efficiency.

* <h4><b> Data Files </b></h4> 

  - <b> Dataset for the project – </b> [Download Dataset](https://github.com/Hamza-Siam/Hamza-Siam/blob/main/Housing%20Data%20-%20Price%20Prediction.xlsx)
  - <b> Code for the project – </b> [View Code](https://github.com/Hamza-Siam/Hamza-Siam/blob/main/House%20Price%20Prediction%20-%20Code.pdf)
