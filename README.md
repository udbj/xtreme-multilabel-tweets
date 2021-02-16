# xtreme-multilabel-tweets
Classification of tweets by 10,000 users

* Dataset can be downloaded from `https://www.dropbox.com/s/kn2dmuczse0ysek/train_tweets.txt.zip?dl=0`
* Like most extreme multiclass/label classification problems, the dataset has a heavily skewed distribution and the final validation accuracy is low

### FastText
* Uses the `fasttext` library by Facebook for classfication of BERT-encoded tweets
* Achieves accuracy of 16.33% on validation set

### FastXML
* Uses the `Refefer/fastxml` library to run the `PFastreXML` text classifier on BERT-encoded tweets
* Achieves accuracy of 20.32% on validation set
