# Education-Industry-projects
#Machine Learning with Deployment to Heroku Cloud Platform


1. The Problem statement:<h1>


#The goal here is to find the chance of admission of a candidate based on his/her GRE Score (out of 340), TOEFL Score (out of 120), rating of the University (out of 5) in which he/she is trying to get admission, Strength of the SOP (out of 5), strength of the Letter Of Recommendation (out of 5), CGPA (out of 10) and the research experience (0 or 1).


2. Application Design:<h1> 



Once we have the data source fixed, the machine learning approach majorly consists of two pipelines:

*The Training Pipeline:



The training pipeline includes data pre-processing, selecting the right algorithm for creating the machine learning model, checking the accuracy of the created model and then saving the model file.

*The Testing Pipeline:



Once the training is completed, we need to expose the trained model as an API for the user to consume it. For prediction, the saved model is loaded first and then the predictions are made using it. If the web app works fine, the same app is deployed to the cloud platform.

3. Pre-requisites:<h1>

![Flask ](https://img.shields.io/badge/Flask-version1.1-green.svg)
![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg)
![HTML ](https://img.shields.io/badge/HTML-Any-green.svg)
![Heroku ](https://img.shields.io/badge/Heroku-account-green.svg)

