# Portfolio


### Profitable/Non-Profitable Users Classification: Is storing this customers info on cloud worth the company's money?

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1wQYXufCnR6DIdIRk7SyKkHd08eclTFY_#scrollTo=tT2zh4o3_WJj)

The cost of enterprise cloud storage can vary greatly dependent on particular use cases. Accessing data, capacity stored, retrieval frequency and network bandwidth all add to the cost. The company will pay extra cost for extra customer info the company is storing for future purpose. The question of whether that user ID is profitable, aka is worth storing should come into consideration to drive a cost-efficiency strategy for the business. <b>This problem can be formulated as a binary classification problem using deep learning to predict whether the user IDs are profitable or not, under the benchmark whether the system records users visit in the 2-week window.</b> <br /> 
The data here are users-log dataset, which was collected in April 2022, with 16 features, including ids, ad revenue, location data, IP address, site host, devices, browser types, operating systems, etc. <br /> 
<b> Model: </b> RNN <br /> 
<b> Modeling Process: </b> Data Collection -> Data Cleaning and Normalization -> RNN Deep Learning Modeling (Baseline Model, Class Weights, Oversampling).

<center><img src="/images/users-classification (2).gif"/></center>


### Pitney Bowes: Early Warning Signal for Pitney Bowes Meters Identifying Failed Meters to Reduce Down-time Risk.

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/Early-Warning-Signal-for-Pitney-Bowes-Meters/blob/main/Final_Report.ipynb) [![Presentation](https://img.shields.io/badge/Presentation-salmon?)](https://github.com/huonghs/Early-Warning-Signal-for-Pitney-Bowes-Meters/blob/main/1-page%20summary%20-%20v5.pdf)

Pitney Bowes is one of the leading solution providers in Postage Meters, which allows businesses to simplify their shipping and mailing process. <b>The goal of this data mining challenge is to predict which meters will fail within the next 7 days in order to reduce down-time risks of meters deployed at Pitney Bowes’ customers to avoid any sort of disruption.</b> The datasets provide charge and discharge information in terms of average time, cycle, rate, volve; total time off, number of restart times, max voltage … Lag data from 1 to 12 for some average time and rate are also provided.<br /> 
The best performing model is Random Forest with highest accuracy score of 67%. While PCA was utilized in an attempt to generate a better model, the performance was not as good as the original dataset.<br /> 
<b> Model: </b> Random Forest, Naive Bayes, Logistic Regression, SVM (Linear), Kernel SVM, Decision Tree, KNeighbors.<br />
<b> Modeling Process: </b> Data Cleaning -> Data Balancing -> Feature Engineering -> PCA -> Applying Classification Algorithms -> Model Tuning.<br />

<center><img src="/images/pitneybowes-gif2.gif"/></center>


### Click Fraud in Digital Advertising: Detecting The Invalid Ad Traffic using Machine Learning

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/adclickfraud/blob/main/Ad_Click_Fraud_Project%20(1).ipynb) 

One of the most prominent problem in digital advertising industry in the last few decades is to minimize ad fraud and to avoid wasting ad spend on invalid and low-quality, bot traffic. A solution for a detecting system, which can proactively predict and prevent ad fraud is a much-needed support for any business, publisher or advertiser. <b>The goal of this project is to investigate users' click behavior, identify features importance and build predictive models that can help advertisers in detecting click fraud from their campaign traffic.</b> The data here is the mobile click-log dataset from TalkingData (the China’s largest independent big data service platform, covers over 70% of active mobile devices nationwide). This project highlights the importance of exploratory data analysis, feature engineering and the use of appropriate algorithms (LightGBM, XGBoost) to deal with imbalanced data.<br />
<b> Model: </b> LightGBM, XGBoost<br />
<b> Modeling Process: </b> Data Cleaning -> Feature Engineering -> Baseline Model -> Model Tuning for Imbalanced Data.<br />

<center><img src="/images/clickfraud-pic5.png"/></center>


### IMDb Movie Reviews: Sentiment Analysis + Text Classification with LSTM - Pytorch and BERT

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1CdSIU5Pn8ojJGegx501UcQNykBy7WbkO#scrollTo=bcSGpPdppzat)

Sentiment analysis is a natural language processing technique used to determine whether data is positive, negative or neutral. Sentiment analysis allows
businesses to identify customer sentiment toward products, brands or services in online conversations and feedback. Thus, it is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs. This IMDB movie reviews dataset has 50K movie reviews with binary labels: postive or negative. <b>The main motive behind this project was to construct a sentiment analysis model that will help understand the sentiment behinds the movie reviews.</b> In this project, I performed data cleaning, EDA and predictive modeling using deep learning algorithms such as BERT and LSTM to achieve this goal. By evaluating the models, BERT gives the highest accuracy score of 86%.<br />
<b> Model: </b> LSTM, BERT<br />
<b> Modeling Process: </b> Data Cleaning -> Tokenization -> Padding -> Building Baseline Model -> Model Tuning.<br />

<center><img src="/images/Imdb-pic3.png"/></center><

### Diabetes Prediction with k-Nearest Neighbor (KNN) Algorithm

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/PIMAIndiansDiabetesData-EDA-KNNModeling/blob/main/Diabetes-EDA%20and%20KNN%20Modeling.ipynb) 

The purpose of this notebook is to predict the oneset of diabetes, classifying whether or not a patient is diabetic, on the basis of certain diagnostic measures in the dataset. I use KNN classification algorithm which will help make a prediction of a class of a target variable based on a defined number of nearest neighbors. The final model is k=11 with the accuracy score of 76%.<br />
<b> Model: </b> k-Nearest Neighbor (KNN)<br />

<center><img src="/images/knn-pic5.png"/></center>


### UCI Heart Disease Data: Multivariate Statistical Analysis 

[![Project Report](https://img.shields.io/badge/Project_Report-blueviolet?)](https://github.com/huonghs/UCI-heart-disease-dataset/blob/main/UCI%20Heart%20Disease%20Data%20Set.pdf)

Multivariate dataset provides and involves a variety of separate mathematical or statistical variables. This Heart Disease Data from UCI is composed of 14 attributes which are age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar,etc. We utilized multiple multivariate statistical methods to get a better understanding of this data. The major tasks we focused on this project include:<br />
<b>- Multivariate Hypothsis Testing:</b> Developed testing on whether there is a significant difference between males and females in heart health indicators (regardless of locations)<br />
<b>- Multivariate Analysis of Variance:</b> Examined if there is a significant difference in heart health indicators between three data sources: Cleveland, Hungary and Switzerland.<br />
<b>- Discriminat and Classification Analysis:</b> Focused on finding linear combinations of variables that best separate the three groups of multivariate observations (Cleveland, Hungary, and Switzerland).<br />
<b>- Principal Component Analysis:</b> Focused on explaining the variance-covariance structure of a set of variables through a few linear combinations of these variables<br />

<center><img src="/images/uci-heart-disease-pic2.png"/></center><br /> 

### Regression Analysis on Seoul Bike Sharing Demand
[![R Markdown](https://img.shields.io/badge/R_-Open_RMarkdown-lightskyblue?logo=R)](https://github.com/huonghs/regression-seoul-bike-share/blob/main/9700_project_updated_v3%20(1).Rmd) [![Project Report](https://img.shields.io/badge/Project_Report-blueviolet?)](https://github.com/huonghs/regression-seoul-bike-share/blob/main/9700%20Group4%20final%20version.pdf)

This report focuses on exploring and analyzing the Seoul Bike Sharing dataset from the Machine Learning Repository at UCI. The dataset contains the count of public bikes rented at each hour, with other weather and holiday information to help support the analysis. We have chosen Bike Count (which is the number of bikes rented) as our response variable since our goal is to understand the demand and build linear models to predict the bike counts using a set of potential predictor variable. We have tested multiple regression models by introducing both numerical and categorical variables (such as tempertaure, functioning_day, hour, solar radiation) and conducted F-Test to understand their interaction term as predictor variables. Lastly, Our last model is going to be built with the AIC Criterion and “Backwards Elimination” procedure to automatically obtain the best fit model. We started with 12 predictor variables, and after completing Backwards Elimination, we find that the best fit model includes the 7 following variables: Solar Radiation, Rainfall, Season, Dew Point Temperature, Humidity,Functioning Day, and Hour. <br />
<b>The AIC value is 6,162.43. Our adjusted 𝑅2 value improved from Model 1 to model 3, increasing from .4332 to .5439.</b><br />

<center><img src="/images/RegressionModel.png"/></center><br /> 



