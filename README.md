# Session28_MachineLearning8
Acadgild Master's in Data Science Course Session28_MachineLearning8 Assignment

In this assignment students have to find the frequency of words in a webpage. 
User can use urllib and BeautifulSoup to extract text from webpage.

Hint:

from bs4 import BeautifulSoup

import urllib.request

import nltk

response = urllib.request.urlopen('http://php.net/')

html = response.read()

soup = BeautifulSoup(html,"html5lib")
