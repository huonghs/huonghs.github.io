# Portfolio


### Profit/Non-Profitable Users Classification: Is storing these IDs on cloud worth the company's money?

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1wQYXufCnR6DIdIRk7SyKkHd08eclTFY_#scrollTo=tT2zh4o3_WJj)

The cost of enterprise cloud storage can vary greatly dependent on particular use cases. Accessing data, capacity stored, retrieval frequency and network bandwidth all add to the cost. The company will pay extra cost for extra user IDs the company is storing for future purpose. The question of whether that user ID is profitable, aka is worth storing should come into consideration to drive a cost-efficiency strategy for the business. 
This problem can be formulated as a binary classification problem using deep learning to predict whether the user IDs are profitable or not, under the benchmark whether the system records users visit in the 2-week window.
The data here are users-log dataset, which was collected in April 2022, with 16 features, including ids, ad revenue, location data, IP address, site host, devices, browser types, operating systems, etc.
<b> Model: </b> RNN
<b> Modeling Process: </b> Data Collection -> Data Cleaning and Normalization -> RNN Deep Learning Modeling (Baseline Model, Class Weights, Oversampling).

<center><img src="/images/UsersClassification.png"/></center>


### Pitney Bowes:Early Warning Signal for Pitney Bowes Meters Identifying Failed Meters to Reduce Down-time Risk.

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/Early-Warning-Signal-for-Pitney-Bowes-Meters/blob/main/Final_Report.ipynb) [![Presentation](https://img.shields.io/badge/Presentation-salmon?)](https://github.com/huonghs/Early-Warning-Signal-for-Pitney-Bowes-Meters/blob/main/1-page%20summary%20-%20v5.pdf)

Pitney Bowes is one of the leading solution providers in Postage Meters, which allows businesses to simplify their shipping and mailing process. The goal of this data mining challenge is to predict which meters will fail within the next 7 days in order to reduce down-time risks of meters deployed at Pitney Bowes’ customers to avoid any sort of disruption. 
The datasets provide charge and discharge information in terms of average time, cycle, rate, volve; total time off, number of restart times, max voltage … Lag data from 1 to 12 for some average time and rate are also provided. 
The best performing model is Random Forest with highest accuracy score of 67%. While PCA was utilized in an attempt to generate a better model, the performance was not as good as the original dataset.
<b> Models: </b> Random Forest, Naive Bayes, Logistic Regression, SVM (Linear), Kernel SVM, Decision Tree, KNeighbors.
<b> Modeling Process: </b> Data Cleaning -> Data Balancing -> Feature Engineering -> PCA -> Applying Classification Algorithms -> Model Tuning.
<center><img src="/images/pitneybowes-pic7.png"/></center>


### Click Fraud in Digital Advertising: Detecting The Invalid Ad Traffic using Machine Learning

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/adclickfraud/blob/main/Ad_Click_Fraud_Project%20(1).ipynb) 

One of the most prominent problem in digital advertising industry in the last few decades is to minimize ad fraud and to avoid wasting ad spend on invalid and low-quality, bot traffic. A solution for a detecting system, which can proactively predict and prevent ad fraud is a much-needed support for any business, publisher or advertiser. 
The goal of this project is to investigate users' click behavior, identify features importance and build predictive models that can help advertisers in detecting click fraud from their campaign traffic. The data here is the mobile click-log dataset from TalkingData (the China’s largest independent big data service platform, covers over 70% of active mobile devices nationwide). This project highlights the importance of exploratory data analysis, feature engineering and the use of appropriate algorithms (LightGBM, XGBoost) to deal with imbalanced data.
<b> Models: </b> LightGBM, XGBoost
<b> Modeling Process: </b> Data Cleaning -> Feature Engineering -> Baseline Model -> Model Tuning for Imbalanced Data.
<center><img src="/images/clickfraud-pic5.png"/></center>


### IMDb Movie Reviews: Sentiment Analysis + Text Classification with LSTM - Pytorch and BERT

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1CdSIU5Pn8ojJGegx501UcQNykBy7WbkO#scrollTo=bcSGpPdppzat)

Sentiment analysis is a natural language processing technique used to determine whether data is positive, negative or neutral. Sentiment analysis allows
businesses to identify customer sentiment toward products, brands or services in online conversations and feedback. Thus, it is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.
This IMDB movie reviews dataset has 50K movie reviews with binary labels: postive or negative. The main motive behind this project was to construct a sentiment analysis model that will help understand the sentiment behinds the movie reviews. In this project, I performed data cleaning, EDA and predictive modeling using deep learning algorithms such as BERT and LSTM to achieve this goal.
By evaluating the models, BERT gives the highest accuracy score of 86%.
<b> Model: </b> LSTM, BERT
<b> Modeling Process: </b> Data Cleaning -> Tokenization -> Padding -> Building Baseline Model -> Model Tuning.

<center><img src="/images/Imdb-pic3.png"/></center>



### Cardio Good Fitness Case Study - Data Analysis and Visualization

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/CardioFitnessDataAnalysis/blob/main/CardioGoodFitness.ipynb)

![image](https://user-images.githubusercontent.com/69947391/150016707-21eb1641-169b-45e3-b9b8-5381c794e70c.png)

### Jersey City - Ctibike Rideas Data in Oct 2021 - Data Analysis and Visualization

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/Citbike_Oct_Data_in_JerseyCity/blob/main/Citibike.ipynb)

![image](https://user-images.githubusercontent.com/69947391/150017983-09bff5bf-fbd2-4c67-8612-e8f78d9fc0f3.png)

### Web Scrapping: Word Frequency in Moby Dick, Or The Whale Novel

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/DataCamp-WebScraping-WordFrequency-in-Novel/blob/main/WordFrequency-in-MobyDick.ipynb)

![image](https://user-images.githubusercontent.com/69947391/150020666-ce91bfe1-cadd-4111-92be-142cb5cc867d.png)
