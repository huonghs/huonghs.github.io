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
<b> Models: </b> Random Forest, Naive Bayes, Logistic Regression, SVM (Linear), Kernel SVM, Decision Tree, KNeighbors.<br />
<b> Modeling Process: </b> Data Cleaning -> Data Balancing -> Feature Engineering -> PCA -> Applying Classification Algorithms -> Model Tuning.<br />

<center><img src="/images/pitneybowes-gif2.gif"/></center><br /> 


### Click Fraud in Digital Advertising: Detecting The Invalid Ad Traffic using Machine Learning

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/adclickfraud/blob/main/Ad_Click_Fraud_Project%20(1).ipynb) 

One of the most prominent problem in digital advertising industry in the last few decades is to minimize ad fraud and to avoid wasting ad spend on invalid and low-quality, bot traffic. A solution for a detecting system, which can proactively predict and prevent ad fraud is a much-needed support for any business, publisher or advertiser. <b>The goal of this project is to investigate users' click behavior, identify features importance and build predictive models that can help advertisers in detecting click fraud from their campaign traffic.</b> The data here is the mobile click-log dataset from TalkingData (the China’s largest independent big data service platform, covers over 70% of active mobile devices nationwide). This project highlights the importance of exploratory data analysis, feature engineering and the use of appropriate algorithms (LightGBM, XGBoost) to deal with imbalanced data.<br />
<b> Models: </b> LightGBM, XGBoost<br />
<b> Modeling Process: </b> Data Cleaning -> Feature Engineering -> Baseline Model -> Model Tuning for Imbalanced Data.<br />

<center><img src="/images/clickfraud-pic5.png"/></center><br />


### IMDb Movie Reviews: Sentiment Analysis + Text Classification with LSTM - Pytorch and BERT

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1CdSIU5Pn8ojJGegx501UcQNykBy7WbkO#scrollTo=bcSGpPdppzat)

Sentiment analysis is a natural language processing technique used to determine whether data is positive, negative or neutral. Sentiment analysis allows
businesses to identify customer sentiment toward products, brands or services in online conversations and feedback. Thus, it is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs. This IMDB movie reviews dataset has 50K movie reviews with binary labels: postive or negative. <b>The main motive behind this project was to construct a sentiment analysis model that will help understand the sentiment behinds the movie reviews.</b> In this project, I performed data cleaning, EDA and predictive modeling using deep learning algorithms such as BERT and LSTM to achieve this goal. By evaluating the models, BERT gives the highest accuracy score of 86%.<br />
<b> Model: </b> LSTM, BERT<br />
<b> Modeling Process: </b> Data Cleaning -> Tokenization -> Padding -> Building Baseline Model -> Model Tuning.<br />

<center><img src="/images/Imdb-pic3.png"/></center><br />

### Diabetes Prediction with KNN Algorithm

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/PIMAIndiansDiabetesData-EDA-KNNModeling/blob/main/Diabetes-EDA%20and%20KNN%20Modeling.ipynb) 

The purpose of this notebook is to predict the oneset of diabetes, classifying whether or not a patient is diabetic, on the basis of certain diagnostic measures in the dataset. I use KNN classification algorithm which will help make a prediction of a class of a target variable based on a defined number of nearest neighbors. The final model is k=11 with the accuracy score of 76%.<br />
<b> Models: </b> KNN<br />

<center><img src="/images/knn-pic4 (1).png"/></center>


