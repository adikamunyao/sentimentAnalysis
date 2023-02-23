# Twitter Sentiment Analysis
## Introduction
**Sentiment**
* When someone feels good about something, it's called a positive feeling, and when they feel bad about something, it's called a negative feeling, those feelings are "sentiment."

Twitter is a social media platform that allows users to share short messages known as tweets. These tweets can be about any topic and can contain a range of sentiments, from positive to negative. Sentiment analysis is the process of using natural language processing and machine learning techniques to identify the emotional tone behind a tweet. It can help to determine whether a tweet is positive, negative, or neutral, and can also provide insight into the opinions and attitudes of Twitter users towards a particular topic or brand. Sentiment analysis on Twitter can be useful for businesses to understand how their brand is perceived by the public, and for individuals to gauge public opinion on a particular issue. Overall, Twitter and sentiment analysis provide a powerful tool for understanding the emotions and attitudes of people on a wide range of topics.

### Fourier transform Sentiment analysis
In mathematical terms, the Fourier transform of a continuous-time signal x(t) is defined as:

X(f) = ∫x(t)e^(-j2πft)dt

where X(f) is the frequency-domain representation of the signal x(t), and f is the frequency in hertz. The Fourier transform maps a function of time into a function of frequency.

The inverse Fourier transform, on the other hand, is used to recover the time-domain signal from its frequency-domain representation. It is defined as:

x(t) = (1/T) ∫X(f)e^(j2πft)df

where T is the duration of the signal.


## Objectives
1. To extract features that capture the frequency of different words or phrases in the text.
2. To capture the underlying patterns and structures in text data that are not readily apparent in the time domain.
3. To obtain insights into the underlying sentiment and emotions expressed in the text.

## Data
The Twitter Sentiment Analysis Dataset is a corpus of 1,578,627 classified tweets, with each tweet marked as 1 for positive sentiment and 0 for negative sentiment. The dataset is based on data from the University of Michigan Sentiment Analysis competition on Kaggle and the Twitter Sentiment Corpus by Niek Sanders. It is recommended to use 1/10 of the dataset for testing and the rest for training. The dataset has been used to achieve a 75% accuracy rate with a simple Naive Bayesian classification algorithm. The use of natural language processing can be helpful in extracting context and identifying features that contribute towards sentiment deduction. However, it is important to note that social informal communication, such as tweets, may not conform to grammatical rules and contain shortened words and overuse of punctuation. Despite these limitations, the dataset provides a good starting point for sentiment analysis modeling.

