# Web-scraping-for-sentiment-analysis-imdb

## Web scraping sci-fi movies on IMDB and Sentiment Analysis the godfather reviews using <strong>Jupyter Notebook, NLP TextBlob, NLTK - VADER</strong>

TextBlob is a python library and offers a simple API to access its methods and perform basic NLP tasks.

Sentiment analysis is basically the process of determining the attitude or the emotion of the writer, i.e., whether it is positive or negative or neutral.

The sentiment function of textblob returns two properties, polarity, and subjectivity.

Polarity is float which lies in the range of [-1,1] where 1 means positive statement and -1 means a negative statement. Subjective sentences generally refer to personal opinion, emotion or judgment whereas objective refers to factual information. Subjectivity is also a float which lies in the range of [0,1].

To use this project on your system First u need to install TextBlob, use: 
`pip install -U textblob`
This will install TextBlob. For the uninitiated – practical work in Natural Language Processing typically uses large bodies of linguistic data, or corpora. To download the necessary corpora, you can run the following command
`python -m textblob.download_corpora`
