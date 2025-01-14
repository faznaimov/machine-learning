# My road to ML

The repository was created to track my progress in Machine Learning related topics in order to organize my knowledge and goals. Includes machine learning projects and showcases in Scikit-Learn, TensorFlow, and Keras.

# Table of Contents
- [My Road to ML](#my-road-to-ml)
- [Table of Contents](#table-of-contents)
- [Mini Projects](#mini-projects)
- [ML Showcase](#ml-showcase)
	- [Raw Python](#raw-python)
		- [Machine Learning](#machine-learning)
		- [Deep Learning](#deep-learning)
	- [Sklearn](#sklearn)
	- [TensorFlow](#tensorflow)
		- [Image Classification](#image-classification)
		- [Natural Language Processing (NLP)](#natural-language-processing-nlp)
		- [Time Series](#time-series)
		- [Other](#other)
- [Courses & Certificates](#courses--certificates)
- [Notes](#notes)
- [Contact](#contact)

# Mini Projects
| Problem | Description | Tech Stack | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [The Simpsons Characters Classification](https://github.com/faznaimov/ml/blob/master/projects/simpsons-classification.ipynb) | CNN,  4 and 6 convolutions, dropout-regularization, data-augmentation | TensorFlow, Matplotlib, Flask, Numpy | [Kaggle](https://www.kaggle.com/alexattia/the-simpsons-characters-dataset/data) | 9/15/2019 | 10/27/2019 |
| [Titanic Disaster Survivor Prediction](https://github.com/faznaimov/ml/blob/master/projects/titanic.ipynb) | XGBoost | XGBoost, Numpy, Pandas, Matplotlib, Seaborn, GridSearch  | [Kaggle](https://www.kaggle.com/competitions/titanic/data) | 08/9/2022 | 08/27/2022 |
| [House Prices Prediction with SKLearn Pipeline](https://github.com/faznaimov/ml/blob/master/projects/house_prices_sk_pipeline.ipynb) | 10 Regression Models, Hyperparameter search using GridSearch and RandomizedSearchCV, SKLearn Pipeline | SKLearn, LightGBM, CatBoost, XGBoost, Numpy, Pandas, Matplotlib, Seaborn, GridSearch, RandomizedSearchCV  | [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) | 12/15/2022 | 12/26/2022 |
| [ML Pipeline for Short-Term Rental Prices in NYC](https://github.com/faznaimov/ml-pipeline-for-short-term-rental-prices) | End to end ML pipeline to predict rental prices for airbnb rentals using MLFlow and Weights and Biases | MLOps, SKLearn, Numpy, Pandas, Matplotlib, GridSearch, MLFlow, Weights and Biases, Pytest | [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) | 1/5/2022 | 1/11/2022 |
| [Salary Predictor Application with FastAPI](https://github.com/faznaimov/salary_predictor_app) | Salary prediction model deployed with FastAPI, DVC pointing to AWS S3 bucket, unit tests and API tests, CI/CD framework using GitHub Actions | MLOps, SKLearn, Numpy, Pandas, Matplotlib, FastAPI, Pytest, AWS, CI/CD | [Census Bureau](https://github.com/faznaimov/salary_predictor_app) | 1/15/2022 | 1/21/2022 |


# ML Showcase
In this section I want to present my knowledge about various ML related algorithms, frameworks, programming languages, libraries and more. Priority is to show how the algorithm works - not to solve complex and ambitious problems.

## Raw Python
### Machine Learning
| Algorithm | Problem | Description | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| Linear Regression | [Childhood Respiratory Disease](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Respiratory_Disease/Respiratory_Disease_Raw_Python.ipynb) | Raw Python | [Dataset](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Respiratory_Disease/Resources/smoking.csv) | 07/20/2022 | 08/27/2022 |
| Logistic Regression | [Gender Recognition by Voice and Speech Analysis](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Voice_Recognition/Voice_Recognition_Raw_Python.ipynb) | Raw Python  | [Dataset](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Voice_Recognition/Resources/voice.csv) | 07/25/2022 | 08/27/2022 |
| Gaussian Distribution Anomaly Detection | [Anomaly Detection](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/anomaly_detection/anomaly_detection.ipynb) | Raw Python  | Dummy Data | 08/29/2022 | 10/15/2022 |
| Decision Tree | [Mashroom Classification](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/decision_tree/decision_tree.ipynb) | Raw Python  | Dummy Data | 08/10/2022 | 10/15/2022 |
| K-means | [K-means Clustering](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/kmeans_raw/kmeans.ipynb) | Raw Python  | Dummy Data | 08/15/2022 | 10/15/2022 |

### Deep Learning
| Algorithm | Problem | Description | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| MLP | [Coffee Roast](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/nn_raw/coffee_roast.ipynb) | 2 layers, Raw Python | Dummy Data | 09/07/2022 | 10/15/2022 |

## Sklearn
| Algorithm | Problem | Description | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| Linear Regression | [Childhood Respiratory Disease](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Respiratory_Disease/Respiratory_Disease.ipynb) | Sklearn | [Dataset](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Respiratory_Disease/Resources/smoking.csv) | 08/19/2019 | 10/20/2019 |
| Logistic Regression | [Gender Recognition by Voice and Speech Analysis](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Voice_Recognition/Voice_Recognition.ipynb) | Sklearn | [Dataset](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Voice_Recognition/Resources/voice.csv) | 08/25/2019 | 10/19/2019 |
| KNN | [Diabetes Test](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/KNN/KNN.ipynb) | Sklearn | [Dataset](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/KNN/Resources/diabetes.csv) | 08/30/2019 | 10/20/2019 |
| SVM | [Exoplanets](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Exoplanets/exoplanet-exploration.ipynb)  | Sklearn | [Dataset](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Exoplanets/Resources/exoplanet_data.csv) | 9/18/2019 | 10/20/2019 |
| Random Forest | [Diabetes Test](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Trees/Trees.ipynb) | Sklearn | [Dataset](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Trees/Resources/diabetes.csv) | 9/24/2019 | 10/20/2019 |
| K-means | [K-means Clustering](https://github.com/faznaimov/ml/blob/master/showcases/machinelearning/Kmeans/Kmeans.ipynb) | Sklearn | Dummy Data | 9/26/2019 | 10/20/2019 |

## TensorFlow

### Image Classification
| Net Type | Problem | Description | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| CNN | [Cats vs Dogs](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/Cats-vs-Dogs/Cats-vs-Dogs.ipynb) | 3 convolutions | [Microsoft](https://www.microsoft.com/en-us/download/details.aspx?id=54765) | 10/07/2019 | 10/27/2019 |
| CNN | [Horses vs Humans](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/horses-vs-humans/horses-vs-humans.ipynb) | InceptionV3, dropout-regularization, data-augmentation | [Dataset](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/horse-or-human.zip) | 10/14/2019 | 10/27/2019 |
| CNN | [Sign Language Detector](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/signlanguage/signlanguage.ipynb) | 2 convolutions, data-augmentation | [Sign Language MNIST](https://www.kaggle.com/datamunge/sign-language-mnist) | 10/19/2019 | 10/29/2019 |

### Natural Language Processing (NLP)
| Net Type | Problem | Description | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| MLP | [BBC News Classification](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/BBC-archive/bbc-archive.ipynb) | 3 layers, global average pooling | [BBC Archive](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/bbc-text.csv) | 10/23/2019 | 11/05/2019 |
| RNN | [Poem Generator](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/poem/shakespeare.ipynb) | Bidirectional LSTM, dropout  | [Shakespeare Sonnets](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/sonnets.txt) | 10/23/2019 | 10/05/2019 |
| CNN/RNN | [Twitter Sentiment Analysis](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/twitter/twitter.ipynb) | Max pooling, LSTM, dropout-regularization, NTLK | [Kaggle](https://www.kaggle.com/kazanova/sentiment140) | 11/13/2019 | 12/10/2019 |

### Time Series
| Net Type | Problem | Description | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| CNN/RNN | [Sunspot Prediction](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/sunspots/sunspots.ipynb) |  1 convolution, 2 LSTM | [Github](https://github.com/jbrownlee/Datasets/blob/master/monthly-sunspots.csv) | 10/29/2019 | 11/17/2019 |

### Other
| Net Type | Problem | Description | Dataset | Creation Date | Last Update |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| MLP | [Smartphone Activity Detector](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/Smartphones/Smartphone_Activity_Detector.ipynb) | 3 layers with 1 hidden layer, ReLu, Softmax, Adam Optimizer | [Dataset](https://github.com/faznaimov/ml/tree/master/showcases/deeplearning/Smartphones/Resources/) | 10/03/2019 | 10/20/2019 |
| MLP | [Credit Card Fraud Detection](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/fraud_detection/fraud_detection.ipynb) | 4-layers, dropout-regularization | [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) | 11/07/2019 | 11/24/2019 |
| Linear Regression | [Gold Futures Prediction](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/Futures-Prediction/Futures-Prediction.ipynb) | TensorFlow | [Investing.com](investing.com) | 11/17/2019 | 11/29/2022 |
| Linear Regression | [Collaborative Filtering Recommender System](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/collaborative_recsys/col_rec_sys.ipynb) | TensorFlow, Recommender System | [MovieLens](https://files.grouplens.org/datasets/movielens/ml-latest-small.zip) | 9/27/2022 | 10/17/2022 |
| MLP | [Content-Based Filtering Recommender System](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/recommender_systems/content_filtering.ipynb) | TensorFlow, Recommender System | [MovieLens](https://files.grouplens.org/datasets/movielens/ml-latest-small.zip) | 9/30/2022 | 10/17/2022 |
| Reinforcement Learning | [Lunar Lander](https://github.com/faznaimov/ml/blob/master/showcases/deeplearning/reinforcement_learning/lunar_lander.ipynb) | TensorFlow | [OpenAI Gym](https://www.gymlibrary.dev) | 9/30/2022 | 10/17/2022 |


# Courses & Certificates
  + [Mathematics for Machine Learning Specialization](https://www.coursera.org/specializations/mathematics-machine-learning) (Coursera - Imperial College London)
  + [Intro to Statistics](https://www.udacity.com/course/intro-to-statistics--st101) (Udacity)
  + [Intro to Inferential Statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201) (Udacity)
  + [Data Structures and Algorithms Course in Python](https://www.udemy.com/course/data-structures-and-algorithms-bootcamp-in-python/l) (Udemy)
  + [Machine Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/USEYWVMLNW4E) (Coursera - Stanford - Andrew Ng)
  + [DeepLearning.AI TensorFlow Developer Specialization](https://www.coursera.org/account/accomplishments/professional-cert/GUKKBJZZDVU5) (Coursera - deeplearning.ai)
  + [Introduction to Machine Learning in Production](https://www.coursera.org/account/accomplishments/verify/WYN72KPRK39X) (Coursera - deeplearning.ai)
  + [Deep Learning Specialization](https://coursera.org/verify/specialization/2NLARPCBTEKK) (Coursera - deeplearning.ai)
  + [Machine Learning DevOps Engineer](https://confirm.udacity.com/SHQMLCWV) (Udacity Nanodegree)

# Notes
Notes from some of the courses above - [Notes](https://github.com/faznaimov/ml/blob/master/Machine_Learning_Notes.pdf)

# Contact
- [Portfolio](https://faznaimov.github.io)
- [LinkedIn](https://www.linkedin.com/in/fazn/)
- [Email](mailto:faz.naimov@gmail.com)
