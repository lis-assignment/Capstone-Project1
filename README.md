### Seattle Housing Market Analysis
**Liulujunjin (Vivian Liu)**    

![](./image/Seatle1.jpg)   

#### Executive summary   

### In this application, a Seattle housing price dataset from kaggle is analyzed, modelled and predicted. The original dataset contained information on 21k houses. The goal of this report is to understand what factors make a house more or less expensive. As a result of the analysis, clear recommendations about house pricing will be provided to the real estate companies.
##### With the real-world high dimensional data, it is important to understand, prepare, and model the dataset to assist a group of real estate agents to promote their house investment and sales   
A serial important steps involves data observation, understanding, cleaning, transformation, plotting, scaling, modeling, evaluation, and recommendation.       
For the data analysis and prediction, several multiple regression models are implemented and compared, including Sequential feature selection, Ridge regularization, and Lasso regularization. Then GridSearchCV is used to optimize the hyperparameter.      
 
The real-world data demonstrates high-dimensional and polynomial features. After comparing several multiple regression models, the powerful machine learning choosed the sequential feature selection as the best model, and recommended 5 best features: sqft_living, view, grade, yr_built, lat
The final results demonstrated that: among all the factors, the most important feature is the living area to affect the house price, the larger the higher, secondly the better view, the higher the price. Moreover, the grade and building year keep the house values.   

#### Rational
Why should anyone care about this question?   

#### The real estate market is very competitive and contains a huge amount of information. 
For any housing investment, it is essential for every real estate investor to understand the market, how to value the similar properties and when to invest a house.   

#### Research Question
What are you trying to answer?   

There are important factors to analyze the housing market.   
To ensure the safe and profitable investments, it is necessary:
* To investigate the most significant facters controlling the housing price.  
* To understand the graphic aspects of housing locations.   
* To build best models through comparing different machine learning techniques.    

#### Data Sources
What data will you use to answer you question?   
 
The current Seattle housing price dataset is from kaggle. The original dataset contained information on 21k houses.    
The housing information includes date, price, bedrooms, bathrooms, sqft_living,sqft_lot, floors, waterfront, view, condition, grade, sqft_above, sqft_basement, yr_built, yr_renovated, zipcode, lat, long, sqft_living15, and sqft_lot15.    

#### Methodology
What methods are you using to answer the question?   

The current housing price dataset is high-dimensional and contains polynomial features.
Before applying multiple regression models, it is important to transform and scale the data for the best results.   
For processing training and testing sets, as the squared error will increase the price difference, it is necessary to use numpy.log function to rescale price (y sets)   
Sequential feature selection (greedy algorithm), Ridge regularization, and Lasso regularizationand are utilized to find the best model and the best features. GridSearchCV is used to process the hyperparameter.   

#### Results
What did your research find?   

##### In this report, the real-world Seatle house price dataset is analyzed using multiple regression models to provide valuable information for the real estate companies and agents. 
To investigate the best factors to affect the house price, important steps are implemented: 
* Data observation indicates that there are mixed data types of columns and unrealistic outlier numbers for price.  
* Therefore, in order to understand the real estate market, the dataset is cleaned and transformed with the 
data cleaning and preparation methods.   
* Since the house price less than 250,000 takes about 95% of the business data, it is important to focus the analysis into this field.      
* Different types of plotting provide general and statistic pictures for the main market, which can also help to increase the total data quality. 
   
The real-world data demonstrates high-dimensional and polynomial features. After comparing several multiple regression models, the powerful machine learning choosed the sequential feature selection as the best model, and recommended 5 best features: sqft_living, view, grade, yr_built, lat
The final results demonstrated that: among all the factors, the most important feature is the living area to affect the house price, the larger the higher, secondly the better view, the higher the price. Moreover, the grade and building year keep the house values.   

#### Next steps
What suggestions do you have for next steps?   

According to the machine learning prediction model generated in this  report, it is useful to compare our predictive results with the estimated market value from the online market information.
It will provide more realistic factors and ideas for the further market research.   

#### Outline of project

[Link to notebook 1](https://github.com/lis-assignment/Capstone-Project1/blob/main/Capstone_Project_1.2.ipynb)   

##### Contact and Further Information   

Vivian Liu   
email: liulujunjin@gmail.com





