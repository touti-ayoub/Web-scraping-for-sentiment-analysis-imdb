# Web-scraping-for-sentiment-analysis-imdb

Data scraping and cleaning done with python using Jupyter Notebook

## Scraped movies:

![Screenshot 2022-11-27 012342](https://user-images.githubusercontent.com/59805646/204113869-be23d97b-2c06-435b-b6f6-5269fa811127.png)


## Scraped reviews for Black Adam movie:

![Screenshot 2022-11-27 012515](https://user-images.githubusercontent.com/59805646/204113891-b6e634e1-d9c7-4440-b199-8553429abfea.png)


Sentiment analysis done with TextBlob, which is a python library that offers a simple API to access its methods and perform basic NLP tasks.

![image](https://user-images.githubusercontent.com/59805646/204113912-083b96ab-9acc-4d1e-bd27-edbbaa73c695.png)


Sentiment analysis is basically the process of determining the attitude or the emotion of the writer, i.e., whether it is positive or negative or neutral.

The sentiment function of textblob returns two properties, polarity, and subjectivity.

Polarity is float which lies in the range of [-1,1] where 1 means positive statement and -1 means a negative statement. Subjective sentences generally refer to personal opinion, emotion or judgment whereas objective refers to factual information. Subjectivity is also a float which lies in the range of [0,1].

To use this project on your system First u need to install TextBlob, use : 

`pip install -U textblob`

This will install TextBlob. For the uninitiated – practical work in Natural Language Processing typically uses large bodies of linguistic data, or corpora. To download the necessary corpora, you can run the following command:

`python -m textblob.download_corpora`
