# 🆂🅴🅽🆃🅸🅼🅴🅽🆃-🅰🅽🅰🅻🆈🆂🅸🆂-🆄🆂🅸🅽🅶-🅿🆈🆃🅷🅾🅽

The principal task of Sentiment Analysis is to find the perspective ,view ,attitude or feeling of a speaker on a particular topic, event or interactionBasicaly its the analysis of an emotionally cahrged text.
	Here we try to analyzethe reviewsposted by people at Imdb. Further the reviews are processed 
analyzed using machine learning procedures, algorithms and other related aspets.

### Algorithms Used
	
	* Support Vector Machine Classifier - `linearSvc`
	* Random Forest Classifer
	* AdaBoost Classfier
	* Naive Bayes Classifier - `MultinomialNB`
	* Bagging Classifier

### Steps in Sentiment Analysis

	1.Formation of Dataset
	2.Processing of Data
	3.Creation of Feature Vector
	4.Classification


## 🅿🆁🅴 🆁🅴🆀🆄🅴🆂🆃🅸🅴🆂


### Environment Setup
 
         -:> python 2.8 or above 3.x recommended

### Dataset

[Download DataSet from here](http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz)

### install modules

1.sklearn
```bash
pip install sklearn
```
2.pickle
```bash
pip install pickle-mixin
```
3.nltk
```bash
pip install nltk
```
in Python IDLE

``` bash
import nltk
nltk.download("stopwords")
``` 

4.numpy

```bash
pip install numpy
```



## 🅷🅾🆆🆆 🆃🅾 🆁🆄🅽

`imdbReviews.py` generates `*.pkl` files which are the training and testing datasets.
First, set the dataset directory in the `imdbReviews.py`, then run the code.
```
python imdbReviews.py
```
now you will get two new .pkl files such as `test.pkl` & `train.pkl`
which are needed for `naive.py`, `svm.py`,`rfc.py`,`bagging.py`,`adaboost.py`.

#### To do prediction, run the following command.

```bash 
python filname.py 
```

`eg:-`

```bash
python naive.py
```
