# Fraudulent Event Detection

# Motivation
The case of fraud is very serious for any company.  Correctly identifying cases of fraud can save a company tremendous money.  However, one must be careful with this.  Incorrectly identifying cases as fraud can lead to a decrease in consumer trust in the company.  Using EventBrite data, our task was to utilize a model in order to identify true fraud cases as often as possible while minimizing the amount of incorrect classification of fraud.  Due to the nature of this data, I am unable to release it to the public.

# Objectives
* Create a model to correctly classify fraud while minimizing amount of false positives
* Make predictions on streaming data
* Create a deliverable in the form of a Flask web application

# Results
* Chose Random Forest classifier with 100 estimators and balanced class weights
    * 16 continuous/boolean features
    
* Test set of 3,546 entries
    * False Positive Rate = 0.0043
    * False Negative Rate = 0.083
    
# Web Application
* Used Jinja2 for showing data
* Web template created using HTML5 and CSS3
* Was unable to completely finish setup of data streaming and connect flask with template

# If there was more time
* Fully integrate data streaming into web application
* Add D3.js visualizations
