persoNews
=========

persoNews is a Twitter-based personalized news aggregator. It is a collection of python programs and wepages (using html and css) running on Flask. This project was deployed on Heroku-Cedar stack, but was taken down from Heroku, because Heroku is going to charge for the addons used in this project. 

persoNews uses ElasticSearch in the background as a search engine to compare documents indexed by news links URL and the body contains 100 most recent tweets of twitter users that tweets that particular news link.


Installation of Components:

  Python
  For this project, we are using Python 2.7. Python can be installed by downloading the installer package from the Python website ("https://www.python.org/download/releases/2.7/")

  Python modules used:

    feedparser
    pyelasticsearch
    elasticsearch
    flask
  
  *All these modules can be installed from command prompt. Type 'pip install modulename'

  Flask
  Flask is used to integrate all the python codes and the hmtl files together. It is easy to manage and it provides simple command to deploy your project to Heroku. 


  ElasticSearch
  To install ElasticSearch, download the installer package from ("http://www.elasticsearch.org/download/") 
  After completing the installation, you can run the ElasticSearch instance by typing './elasticsearch -f' in you command     prompt, from your local ElasticSearch folder.

Getting Started
  
  Clone this repository and put it inside your Flask app folder
  Start ElasticSearch instance from your local machine.
  Run TwitterSearchV2.py to populate data inside your ElasticSearch.
  Run routes.py to start the app.
    Now you can access persoNews from your local machine ('http://localhost:5000')
  




