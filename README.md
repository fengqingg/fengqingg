<h1 align="center">Hi there 👋! I'm Feng Qing</h1>

<h3 align="center"><i>Physics undergraduate</i></h3>

<div align="center">

[![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chua-feng-qing/)&nbsp;&nbsp;
[![Kaggle Badge](https://img.shields.io/badge/-Kaggle-23BFFF?style=flat&logo=Kaggle&logoColor=white)](https://www.kaggle.com/fengqingg)&nbsp;&nbsp;
[![Stratascratch Badge](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)](https://platform.stratascratch.com/user/fengqingg)&nbsp;&nbsp;
    
    
</div>

<br>

I'm a physics undergraduate who loves using data to solve issues. I have been using Python to simulate and solve physics equations. I got introduced to data science during year 3 and since then, I have studied and, more recently, worked with data science and machine learning algorithms. For more details about my projects and each solution, they are described in the data science project section.

### Analytics Tools

* **Data Collection and Storage:** SQL and MySQL

* **Data Processing and Analytics:** Python, R, Jupyter and Spyder.

* **Data Visualization:** Seaborn and Matplotlib.

* **Machine Learning Modeling:** Classification, Regression, Clusterization, and Recommendation.

## Data Science Projects

* ### [S&P500 Forecast](https://github.com/fengqingg/SANDP500)

    As a beginner investor, I'm always looking for ways to improve my investment strategy and make more informed decisions.Thus I explored methods that can help me and I have created two models which can help me predict when to buy and sell stocks. I have downloaded historical data of the S&P500 from kaggle, which is an index of 500 large-cap stocks traded on the US stock market, which is then analyzed to see the trend and seasonality of the data. First, I used LSTM (Long Short-Term Memory) which is a type of neural network that's become increasingly popular in recent years, followed by ARIMA(AutoRegressive Integrated Moving Average) which is a classic statistical model that's been used for decades to forecast the data.
    

* ### [Anime Recommendation System](https://github.com/fengqingg/Anime-Recommendation)

    I enjoy watching anime and came up with an anime recommendation system to recommend me anime base on my preferences. This dataset is downloaded from Kaggle and contains information on user preference data from 73,516 users on 12,294 anime. I used Content-Based Filtering to create a function which allows me to get similar animes base on an input anime. It uses TF-IDF vectorizer to convert the list of genres for each anime into a feature matrix, and then using the cosine similarity metric to compute the similarity between each pair of anime based on their genre features to recommend. Then I used Collaborative Filtering which analyzes the past behavior of users to identify those with similar preferences and uses Pearson correlation coefficient to determine their similarity and recommend highly rated animes.


* ### [Diabetes Prediction in R](https://github.com/fengqingg/Diabetes-Classification)

    This dataset is downloaded from Kaggle and it originated from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. The best model was linear SVM with an accuracy of 76% and lowest false positive result. The result was limited by the small sample size of the dataset which introduced high variance in the model.

* ### [Loan Defaulter Prediction](https://github.com/fengqingg/Loan-Prediction)

    This dataset is belongs to a Hackathon organized by "Univ.AI". An organization wants to predict who possible defaulters are for the consumer loans product based on historic customer behavior. Possible defaulters will be with Risk_Flag == 1 and 0 for not possible for being a defaulter. After using several machine learning models and GridSearch, the best model is the random forest classifier with 93.4% accuracy.

* ### [Titanic Classification](https://github.com/fengqingg/Titanic)

    This project is a machine learning competition hosted by Kaggle, in which participants are tasked with predicting which passengers survived the Titanic shipwreck. This is a beginner competition which I attempted after learning the basics of machine learning and tried to improve my machine learning skills by reading other users notebooks. After learning different feature selection techniques, I managed to obtain a model accuracy of 82.1% and a public score in the competition of 76.8%

## Physics Simulation Projects

* ### [Brachistochrone curve](https://github.com/fengqingg/Brachistochrone-curve)

    An analysis of a simplified Brachistochrone problem. First by calculating the time needed to reach x=pi, then solving the ODE using fourth-order Runge-Kutta method (RK4). Eventually, optimizing the Brachistochrone equation parameters suchs that the time to reach the bottom of the equation with a mass is the shortest.

* ### [Waste Optimization](https://github.com/fengqingg/Waste-Optimization-Analysis)

    An analysis of optimization problem using numerical methods. The first part of the problem optimizes the net profit of the company using quadratic interpolation. Then a root bisect method is used to find the amount of tax the mayor should set to obtain the desired amount of waste to burn. We then derive a Newtwon-Raphson method using approximation to find the root of the tax function and talk about its limitations.



## Other Projects

* ### [Pentago Game](https://github.com/fengqingg/Pentago)

    Pentago is a two-player abstract strategy board game invented by Tomas Flodén. Like chess, pentago is a two player game and the goal of the two players is to make the other player lose (or at least tie). In this notebook, pentago is coded with Python using Numpy with two available game modes, Player versus Player (PVP) mode or Computer bots with two level of difficulty.
