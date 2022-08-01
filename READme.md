**Tweet Topic Based Model**

*Topic Model based tweets*


PYTHON ENVIRONMENT
------------------
Enter tweetModel directory and run the following command to install pipenv module to create an standalone virtual environment::
    $ pip install pipenv
    $ pip install notebook

Create virtual environment::    
    $ pipenv shell

Install all main dependencies::   
    $ pipenv install

To build and test the model run::
    $ py twtModel.py

ALTERNATIVE CODE EXECUTIONS
---------------------------

To run using Jupyter Notebook Environment, move to /tweetModel directory and run::
    $ jupyter notebook 

To run in Python Interactive Shell you can change the third parameter to number of your choice::
    $ python
    $ from twtModel import *
    $ print(display_topics(saved_lda_model, tf_feature_names, 10))




"# TweetModel" 
