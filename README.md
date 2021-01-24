# Natural-language-processing-and-a-Sentiment-classifier


This repository is all about the natural language processing.

Here i used Dataset from https://www.kaggle.com/kazanova/sentiment140 which is good dataset for text processing

Before we start we need required python package and can be downloaded by following command

1. conda install Pandas - we need this for data manipulation
2. conda install numpy – for numerical calculation
3. conda install spacy – one of beautiful package for text processing
            python -m spacy download en_core_web_sm  A small version of language model for English
            we can download other language models depending upon your work from here https://spacy.io/usage 
4. ‘re’ this package already comes with python. ‘regrex’ a alternative to this lib can be install as conda install regrex and have a try  - A mathematical representation of languages.
For translation and language detection: Language code:https://www.loc.gov/standards/iso639-2/php/code_list.php


Now, we are going forward to the next step

1.	Load the dataset and go through the data and see what is inside for us
2.	Check for features and target variables and leave out the rest
3.	Check for balance in the each class in target column
4.	Feature Extraction from the tweets i.e our feature column
     i.	We will do some calculation and analysis and save it as column wise. These are word count, total characters, average word length, Stop words count(most used word sometime unnecessary for us and for model too), @, # count, digits count, upper case count and many more one can think of
5.	 Data cleaning and pre processing
     i.	Lower case conversion of each tweets
    ii.	Contraction to Expansion ex – he’ll to he will Source: https://stackoverflow.com/questions/19790188/expanding-english-language-contractions-in-python
   iii.	Count and removal of emails and URLs
    iv.	Special Characters, common words, rare words and punctuation removal
     v.	HTML tags removal
6.	Visualization using wordcloud and matplotlib 
7.	Notebook also contain some advanced text processing and feature extraction operation
8.	Choosing the best machine learning models for text classification
