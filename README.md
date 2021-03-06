# Sentiment Analysis 
**This is the bachelor's degree final project of [Computer Engineering, Bu-Ali Sina University](http://eng.basu.ac.ir/en/ce).**
## Abstract
Our decisions have a great relationship with the opinions of others. As an organization, this can be more valuable to find out how customers think about their products and services. In this notebook, we will use data samples of review texts about some products on Amazon. By finding statistical relationships between words, we are going to create a reasonable model that can predict if costumers have a negative or positive opinion on the given product.
Before training the model, The data preprocessed by removing stopwords, punctuation, etc. Some data exploratory analysis is done afterward to draw some insight. Then using ANOVA Test right features(words) is extracted. The model that is used in this project is Naive Bayes. Naive Bayes is a simple but optimal classifier that can do a reasonable job on text classifying (visit here for more information). In conclusion, to test the model, different scores are calculated as a form of confusion matrix that, in general, gives an accuracy number between 80 to 90 percent. 

## Installation
For a smoother process, use [Google Colab](https://colab.research.google.com/) and upload the data folder there or in your Google Drive. As an alternative, you can use the Jupyter notebook in Anaconda and install additional packages with Conda.
## Cleaning
Our data befor cleaning:
![Data Frame](images/data.png)
Data after cleaning words with digits, punctuations and stop words then stemming them.
![Data Frame](images/data-pro.png)

#### Representing data using Document-term Matrix
![Document-term Matrx](images/dtm.png)
## EDA
Word Cloud of negative reviews:
![Word Cloud](images/blackwordcloud.png)
Word Cloud of positvew reviews:
![Word Cloud](images/whitewordcloud.png)
## Feature Extraction
In this section, words that have the same mean frequency in both low-rated (negative) and high-rated (positive) will be removed and use only those words that are more discriminating as the features to train our model.
![Word Cloud](images/mfw.png)
## Training
In this section, our model will be trained using the Naive Bayes Classifier.

## Testing
The picture below is the testing result.
#### Confustion Matrix
![LCS occurance distribution](images/conf-matrix.png)

