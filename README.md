# Twitter Tweets : Sentiment Analysis using DistilBERT

Here we used DistilBERT model to find sentiments for tweets, using dataset from HuggingFace library. 

Dataset used is : [tweet_eval](https://huggingface.co/datasets/tweet_eval) from datasets library

It can be imported in Colab using :
```
!pip install datasets
from datasets import load_dataset
dataset = load_dataset("tweet_eval", "sentiment")
```
There are many options available instead of 'sentiment', like 'positive', 'emoji' etc


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

