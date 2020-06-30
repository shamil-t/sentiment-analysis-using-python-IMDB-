# 🆂🅴🅽🆃🅸🅼🅴🅽🆃-🅰🅽🅰🅻🆈🆂🅸🆂-🆄🆂🅸🅽🅶-🅿🆈🆃🅷🅾🅽



## 🅿🆁🅴 🆁🅴🆀🆄🅴🆂🆃🅸🅴🆂


### Envirnment
 
         -:> python 2.8 or above 3.x recommended
### Dataset
   
     [DataSet Download from here](http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz)

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
