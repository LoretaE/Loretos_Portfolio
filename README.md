# Loretos_Portfolio

## [Project 4: Customers Age and District Impact on the Mortgage Amount in Lithuania](https://github.com/LoretaE/Mortgages)

### Project overview:

The main results of the project:
* Analysed and visualised customer's age group and district impact on the maximum amount of mortgage.

Data set obtained from [Registrų centras](https://www.registrucentras.lt/p/1561) with Creative Commons Attribution 4.0 
([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.lt)) license. Data cleaning, missing data management, 
detecting and removing outliers were performed. 

Technologies used:
* Python
* Pandas
* Seaborn
* Matplotlib

### Distribution of mortgages by age
![hi_img.png](images%2Fhi_img.png)

### Distribution of mortgages in different districts
![hi_img_1.png](images%2Fhi_img_1.png)

### Distribution of mortgages by age in different districts
![hi_img_2.png](images%2Fhi_img_2.png)

### Conclusions
1. There is a correlation between client's age and max amount of mortgage, except 3 districts (Vilnius, Marijampolė and 
Tauragė).
2. Districts have an impact on the mortgages as well - the largest contractual mortgages were granted in 4 largest 
districts (Vilnius, Klaipėda, Kaunas and Šiauliai).

## [Project 3: Predicting Property Prices](https://github.com/LoretaE/RealEstate)

### Project overview:
Developed the model for predicting the house price, taking into account different characteristics of the property: type,
location, house area, number of rooms and floors, year of construction, land area. 

Data obtained from www.kampas.lt using web scraping. Data cleaning, missing data management, coding of categorical 
variables, standardisation of numerical data were performed.

In order to eliminate price extremes (insufficient data to train the model), house prices were analysed using a price 
histogram. The decision was taken for model developing to use house price data up to €0.5 million (excluding 5% of the data).

### Models used to predict house prices:
* Linear Regression
* Random Forest
* Neural Networks

Technologies used:
* Python
* Requests
* BeautifulSoup
* Pandas
* Numpy
* Scikit-learn
* TensorFlow/Keras
* Plotly dash
* Seaborn

### Correlation Matrix - Heatmap
![](/images/RE_corr.png)

### Pairplot - relationships in a dataset
![](/images/RE_pairplot.png)

### Linear Regression and Random Forest. Test vs Predicted price
![](/images/RE_LR_RF.png)

### Neural Networks. Test vs Predicted price
![](/images/RE_NN.png)

### Conclusions
Models evaluated using RMSE, r2 score and cross-validation. 
The most accurate is the Random Forests model (60%).  Factors limiting the accuracy: (1) the amount of data used to 
train and test the model (3,400 homes for sale), (2) the price is also influenced by other features that were not used 
in the development and testing of the model (as only about 1/3 of the homes had such information), (3) the uniqueness 
of the property or location (e.g. a house with a lake view).




## [Project 2: Prediction of Emotions](https://github.com/LoretaE/EmotionPrediction)
### Project overview:
Created the model, which identifies and classifies different emotions in a text, such as joy, anger & fear. Model can be used in the analysis of social media posts, customer reviews or conversations.
Used dataset "Emotion Dataset" from Kaggle and performed text cleaning, tokenization. Created and trained models, using CNN, RNN or LSTM for emotion recognition. Evaluated model performance using metrics and improved the model. Interactivity has been developed to allow the user to enter text and check how the model recognises emotions.

Technologies used:
* Python
* TensorFlow/Keras
* NLTK
* Scikit-learn
* Pandas

### Model accuracy trend

![](/images/ER_acc_trend.png)

### User interactivity 
![](/images/ER_interactivity.png)

## [Project 1: Health Index Analysis and Prediction](https://github.com/LoretaE/SveikatosAnalize)
### Project overview:
Data preparation for machine learning, selection of machine learning models, model training and evaluation, hyperparameter tuning and model optimisation. 

Models used for data analysis and predictions: 
* Linear Regression
* K-means
* Random Forest
* Logistic Regression
* DBSCAN

### Health Index Prediction
![](/images/HI_prediction.png)
