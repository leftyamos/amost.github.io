# Data Science Portfolio by Amos Tai

A portfolio that contains a compilation of projects that I created which utilises the fundamentals of data analysis, machine learning, deep learning and digital signal processing. Most of the projects are made using the Python programming language. 


<h2 align="center">PROJECTS</h2>

### 1. Rhode Island Police Activity
This [project](https://github.com/leftyamos/amost.github.io/blob/master/Analyzing_Rhode_Island_Police_Activity.ipynb) is a data visualization project that explores the police activities in Rhode Island using various EDA methods to visualize the different types of violations committed based on race, gender, time of day and other related variables. The dataset can be found [here](https://assets.datacamp.com/production/repositories/1497/datasets/62bd9feef451860db02d26553613a299721882e8/police.csv).

### 2. NBA Position Classification (Multi-Class) with an app.
The goal for this [project](https://github.com/leftyamos/amost.github.io/blob/master/NBA_Classification.ipynb) is to determine if the modern NBA starting from 2010-2011 season until 2019-2020 season is truely positionless and if it isn't, can a player be classified on his position based on their stats. The project analyse the relationships between the features and the target positions. A dummy classifier is used as a baseline for our ML model with several classification models created and compared their scores. The models with a decent score will be chosen for evaluation and validation as well as undergoing gridsearch to find the best hyperparameters. A pipeline is also used with a data scaler to improve the performance of the model. 
The [dataset](https://www.basketball-reference.com/leagues/NBA_2011_per_game.html) [is](https://www.basketball-reference.com/leagues/NBA_2012_per_game.html) [taken](https://www.basketball-reference.com/leagues/NBA_2013_per_game.html) [from](https://www.basketball-reference.com/leagues/NBA_2014_per_game.html) [Basketball Reference](https://www.basketball-reference.com/leagues/NBA_2015_per_game.html) [from](https://www.basketball-reference.com/leagues/NBA_2016_per_game.html) [the](https://www.basketball-reference.com/leagues/NBA_2017_per_game.html) [2010-2011 season](https://www.basketball-reference.com/leagues/NBA_2018_per_game.html) [until](https://www.basketball-reference.com/leagues/NBA_2019_per_game.html) [2019-2020 season](https://www.basketball-reference.com/leagues/NBA_2020_per_game.html), which is a decade worth of data. 
An app created using [Streamlit](https://www.streamlit.io/) can be found [here](https://share.streamlit.io/leftyamos/nba_streamlit_app/main/nba_streamlit.py) with the [source code](https://github.com/leftyamos/nba_streamlit_app).

### 3. Metal & Rocks Classification (Binary)
The dataset is taken to UCI Machine Learning Repository where the goal is to differentiate between a metal cylinder and a cylindrical rock based of the sonar signals bouncing off of them. This [project](https://github.com/leftyamos/amost.github.io/blob/master/Mines%20%26%20Rocks.ipynb) uses various machine learning methods to model and classify the two different types. The data was also scaled and a pipeline was used to improve the performance of the model.
The dataset was also applied to a neural network model in [Keras](https://github.com/leftyamos/amost.github.io/blob/master/Keras_Binary_Classification.ipynb) with its performance evaluated with different models. The dataset can be found [here](https://archive.ics.uci.edu/ml/machine-learning-databases/undocumented/connectionist-bench/sonar/sonar.all-data)

### 4. Music Genre Classification (Multi-Class)
Music Genre Classification uses Librosa which is an audio and music analysis python library. This [project](https://github.com/leftyamos/amost.github.io/blob/master/Librosa_Music_Classification.ipynb) classified the genre of music from the GITZAN dataset based on their properties by using different types of machine learning and deep learning models created. The dataset can be found [here](https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification?).

### 5. Fruit Classification (Multi-Class)
A simple dataset of fruits was analyze and used as a [classification problem](https://github.com/leftyamos/amost.github.io/blob/master/ML_Multi_Class_Classification.ipynb) by using different machine learning models with pipeline implimented. Another [approach](https://github.com/leftyamos/amost.github.io/blob/master/fruit.ipynb) using feature engineering instead of scaling while also removing outliers was conducted. The dataset can be found [here](https://raw.githubusercontent.com/susanli2016/Machine-Learning-with-Python/master/fruit_data_with_colors.txt).

### 6. Wheat Kernel Seeds Classification (Multi-Class)
[Wheat Kernel Seeds](https://github.com/leftyamos/amost.github.io/blob/master/seed_class_alt.ipynb) uses a dataset taken from UCI Machine Learning Repository where it is analyze and train using multiple machine learning models to classify different types of seeds. The models are then chosen based on different evaluation scores. The dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/seeds).

### 7. Loan Status Classification (Binary)
This classification [problem](https://github.com/leftyamos/amost.github.io/blob/master/Loan_Status_Classification.ipynb) is to classified if an applicant is able to take a home loan based on several factors. Dataset undergoes pre-processing by imputing the missing values based on statistical methods and categorical values from features were converted to numerical values based on several labelling methods. The dataset can be found [here](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/#ProblemStatement).

### 8. Big Mart Sales Prediction Problem (Regression)
The [project](https://github.com/leftyamos/amost.github.io/blob/master/Big_Mart_Sales_Prediction.ipynb) is to build a predictive model and predict the sales of each product at a particular outlet with the dataset taken from [here](https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#ProblemStatement). The dataset undergoes pre-processing by imputing missing values based on statistical methods and categorical values were encoded by dummy variables.

### 9. Student Performance Grade
This dataset is taken from student achievement in secondary education of two Portuguese schools where it shows the performance grades of students based on various variables. The dataset is analyzed and train to use as a [Feature Selection problem](https://github.com/leftyamos/amost.github.io/blob/master/Student%20Performance%20Grade.ipynb). The dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

### 10. Wine Classification and Quality Prediction
This [project](https://github.com/leftyamos/amost.github.io/blob/master/Wine_Classification_%26_Quality_Prediction.ipynb) analyzes the properties of red and white wine and classified them based on type and quality using a neural network. [Another](https://github.com/leftyamos/amost.github.io/blob/master/wine_class_alt.ipynb) alternate take on the same dataset is used to classified the type of wine using different machine learning models with pipeline implemented, pre-processing by removing outliers and scaling of the data and evalutation of the models by observing their Precision-Recall Curve and ROC Curve. The dataset can be found [here](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/).

### 11. Yelp Ratings
A NLP [project](https://github.com/leftyamos/amost.github.io/blob/master/NLP_Classification_Yelp.ipynb) which analyze yelp reviews and predict them as either positive or negative ratings. The dataset can be found [here](https://www.kaggle.com/c/yelp-recsys-2013/data?select=yelp_test_set.zip).

### 12. Twitter Disaster Tweets
A NLP [project](https://github.com/leftyamos/amost.github.io/blob/master/NLP_Twitter_Project.ipynb) which analyzes a set of twitter tweets to predict which tweets are about a real disaster by using various machine learning models. The dataset can be found [here](https://www.kaggle.com/c/nlp-getting-started/data).

### 13. Boston Housing Price (Regression)
The famous Boston Housing Price dataset is mostly used for regression problems. This [project](https://github.com/leftyamos/amost.github.io/blob/master/Boston_Housing_Price.ipynb) explores using different types of regression models as well as using XGBoost to find the best predictive model.

### 14. HR Analytics Challenge (Binary)
This [project](https://github.com/leftyamos/amost.github.io/blob/master/HR_Promotion_Classification.ipynb) is based on a [competition](https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/) to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process. The dataset is analyze and pre-process by imputing missing values and dealing with outliers, some feature engineering was conducted and categorical values were encoded before training of the model. The dataset is imbalance so a seperate oversampled dataset was created for training too. Now there are two datasets to be train, the original and the oversample dataset. Both datasets were train with different models and were evaluated with different evaluation metrics, one of them is their F1 scores.


<h2 align="center">KAGGLE COMPETITION</h2>

### 1. Titanic: Machine Learning from Disaster
[Titanic: Machine Learning from Disaster](https://www.kaggle.com/leftyamos/titanic-survival-using-random-forest) is a very classic knowledge competition on Kaggle in which the goal is to create a machine learning model that predicts which passengers survived the Titanic shipwreck. The dataset can be found [here](https://www.kaggle.com/c/titanic/data) in Kaggle.

### 2. House Prices: Advanced Regression Techniques
[House Prices: Advanced Regression Techniques](https://github.com/leftyamos/amost.github.io/blob/master/house.ipynb) is a knowledge competition on Kaggle in which the goal is to create a machine learning model using regression to ppredict the final price of each home. The dataset can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) in Kaggle.

### 3. Digit Recognizer
[Digit Recognizer](https://github.com/leftyamos/amost.github.io/blob/master/digit_recongnizer.ipynb) is a knowledge competition on Kaggle in which the goal is to indentify digits from a dataset of tens of thousands of handwritten images. This project uses a neural network model to classified the images. The dataset can be found [here](https://www.kaggle.com/c/digit-recognizer/data) in Kaggle.

### 4. Bike Sharing Demand
This [project](https://github.com/leftyamos/amost.github.io/blob/master/Bike_Rental_Prediction.ipynb) is an old [Kaggle competition](https://www.kaggle.com/c/bike-sharing-demand) which objective is to forecast the demand of bikes rented. The projects goes through several regression models and uses Root Mean Squared Logarithmic Error as a metric for evaluation. 






