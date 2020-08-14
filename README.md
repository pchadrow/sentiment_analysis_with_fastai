# Tweet Sentiment Extraction - Kaggle

Note: This notebook was created and run in Google Colab. To duplicate and rerun this notebook please import this notebook into colab along with the csv files. 

## Purpose
This project was done in response to the [Kaggle Tweet Sentiment Extraction](https://www.kaggle.com/c/tweet-sentiment-extraction) dataset. Unfortunately, this competition had already come to an end, and I was unable to receive a score for my submission. This data was chosen to both familiarize myself with the process of kaggle competitions and due to the interesting challenge posed within NLP and the analyzation of tweets. 

## Summary
For this project, the fastai library was used and the [ULMFiT method](https://humboldt-wi.github.io/blog/research/information_systems_1819/group4_ulmfit/), popularized by Jeremy Howard and Sebastian Ruder, was applied as a starting point. [AWD-LSTM](https://yashuseth.blog/2018/09/12/awd-lstm-explanation-understanding-language-model/) (Average Stochastic Gradient Desecnt Weight Dropped Long Short-Term Memory) was used as our primary form of neural network. From here, a sentiment classifier was built to predict the sentiment of each tweet. Intrinsic attention was then used as our primary method for determination of key words and phrases that resulted in our classification. A custom function was built to output these key words/phrases as our 'selected text' per the kaggle competition. 

## Presentation Overview
For a quick overview of our project, results, and conclusions; please take a look at our brief [non-technical presentation](https://github.com/pchadrow/sentiment_analysis_with_fastai/blob/master/Twitter%20Sentiment%20with%20Fastai.pdf)