## Portfolio

### Profit/Non-Profitable Users Classification: Is storing these IDs on cloud worth the company's money?

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1wQYXufCnR6DIdIRk7SyKkHd08eclTFY_#scrollTo=tT2zh4o3_WJj)

The cost of enterprise cloud storage can vary greatly dependent on particular use cases. Accessing data, capacity stored, retrieval frequency and network bandwidth all add to the cost. The company will pay extra cost for extra user IDs the company is storing for future purpose. The question of whether that user ID is profitable, aka is worth storing should come into consideration to drive a cost-efficiency strategy for the business. 

This problem can be formulated as a binary classification problem using deep learning to predict whether the user IDs are profitable or not, under the benchmark whether the system records users visit in the 2-week window.

The data here are users-log dataset, which was collected in April 2022, with 16 features, including ids, ad revenue, location data, IP address, site host, devices, browser types, operating systems, etc.

<b> Model: </b> RNN
<b> Modeling Process: </b> Data Collection -> Data Cleaning and Normalization -> RNN Deep Learning Modeling (Baseline Model, Class Weights, Oversampling).

<center><img src="/images/UsersClassification.png"/></center>


### Pitney Bowes:Early Warning Signal for Pitney Bowes Meters Identifying Failed Meters to Reduce Down-time Risk.

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/Early-Warning-Signal-for-Pitney-Bowes-Meters/blob/main/Final_Report.ipynb)[![Presentation](https://img.shields.io/badge/Presentation-salmon?)](https://github.com/huonghs/Early-Warning-Signal-for-Pitney-Bowes-Meters/blob/main/1-page%20summary%20-%20v5.pdf)

Pitney Bowes is one of the leading solution providers in Postage Meters, which allows businesses to simplify their shipping and mailing process. The goal of this data mining challenge is to predict which meters will fail within the next 7 days in order to reduce down-time risks of meters deployed at Pitney Bowes’ customers to avoid any sort of disruption. 

The datasets provide charge and discharge information in terms of average time, cycle, rate, volve; total time off, number of restart times, max voltage … Lag data from 1 to 12 for some average time and rate are also provided. 

The best performing model is Random Forest with highest accuracy score of 67%. While PCA was utilized in an attempt to generate a better model, the performance was not as good as the original dataset.

<b> Models: </b> Random Forest, Naive Bayes, Logistic Regression, SVM (Linear), Kernel SVM, Decision Tree, KNeighbors.
<b> Modeling Process: </b> Data Cleaning -> Data Balancing -> Feature Engineering -> PCA -> Applying Classification Algorithms -> Tune Model.

<center><img src="/images/pitneybowes-pic5.png"/></center>



![image](https://user-images.githubusercontent.com/69947391/150016262-517b6d65-b7f4-406d-abb4-b1dda50560b0.png)

### Ames Housing Prices Dataset - EDA and Advanced Regression (WIP)

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/KaggleHousingPriceEDA/blob/main/Kaggle-HousingPrices.ipynb)

![image](https://user-images.githubusercontent.com/69947391/150015685-e6c47bb9-e9f2-4512-842a-4e524124964d.png)

### Cardio Good Fitness Case Study - Data Analysis and Visualization

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/CardioFitnessDataAnalysis/blob/main/CardioGoodFitness.ipynb)

![image](https://user-images.githubusercontent.com/69947391/150016707-21eb1641-169b-45e3-b9b8-5381c794e70c.png)

### Jersey City - Ctibike Rideas Data in Oct 2021 - Data Analysis and Visualization

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/Citbike_Oct_Data_in_JerseyCity/blob/main/Citibike.ipynb)

![image](https://user-images.githubusercontent.com/69947391/150017983-09bff5bf-fbd2-4c67-8612-e8f78d9fc0f3.png)

### Web Scrapping: Word Frequency in Moby Dick, Or The Whale Novel

[![](https://img.shields.io/badge/Jypyter-Open_Notebook-EE4C2C?logo=Jupyter)](https://github.com/huonghs/DataCamp-WebScraping-WordFrequency-in-Novel/blob/main/WordFrequency-in-MobyDick.ipynb)

![image](https://user-images.githubusercontent.com/69947391/150020666-ce91bfe1-cadd-4111-92be-142cb5cc867d.png)
