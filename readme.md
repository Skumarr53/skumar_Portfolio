# List of Projects

- [**Web Scraping**:](#web-scraping)
  - [Web crawler for scraping stock fundamentals](#web-crawler-for-scraping-stock-fundamentals)
- [**Machine Learning**](#machine-learning)
  - [Used Car Price Prediction - MachineHack](#used-car-price-prediction---machinehack)
  - [Amazon Food Reviews](#amazon-food-reviews)
  - [Quora Question Similarity](#quora-question-similarity)
  - [Netflix Recommendation: winners solution Implementation](#netflix-recommendation-winners-solution-implementation)
  - [Understanding PCA through image visualization](#understanding-pca-through-image-visualization)
- [**Deep Learning**](#deep-learning)
  - [Image Caption Generator](#image-caption-generator)
  - [Machine Translation - Transformer based](#machine-translation---transformer-based)
- [**Web Development**](#web-development)
  - [Building Portfolio website using Django - Heruko](#building-portfolio-website-using-django---heruko)
## **Web Scraping**:
### [Web crawler for scraping stock fundamentals](https://github.com/Skumarr53/Stock-Fundamental-data-scraping-and-analysis)

Topics: *Web scraping, Automation, Selenium, BeautifulSoup, stock investing*

Built a web crawler to allow investors to choose fundamentally sound stocks for long term investment by generating review plots automatically. Web crawler crawls selected stock pages, scrapes historical stock data, and generates plot on the fly.

-------


## **Machine Learning**

### [Used Car Price Prediction - MachineHack](https://github.com/Skumarr53/Used-Car-Price-Prediction)

Topics: *Regression, sklearn pipeline, Flask, HTML, JQuery, Docker, AWS* 

**AWS link**: http://usedcarpricepredict-env.eba-jdefnbzx.us-east-1.elasticbeanstalk.com/

#### Demo:

![](https://raw.githubusercontent.com/Skumarr53/Used-Car-Price-Prediction/master/Snapshots/working_app.gif)
<div style="text-align:center"><i>working App developed using Flask</i></div><br>

Built an end-to-end feature transformation and model selection pipeline for predicting the price of used Cars, helping buyers to make an informed purchase. Applied transformation, appropriate techniques for Encoding categories to numbers, then trained various models. **Gradient Boosting Regressor** turns out to be the best model with  Mean Squared Logarithmic Error (MSLE) of **0.033**. Designed an interactive Web application for model deployment using **Flask** framework and Hosted on [**AWS**](http://usedcarpricepredict-env.eba-jdefnbzx.us-east-1.elasticbeanstalk.com/) using Elastic Beanstalk service via **Docker** image.

-------
### [Amazon Food Reviews](https://github.com/Skumarr53/Amazon-Food-Reviews-Kaggle)

Topics: *Sentiment analysis, sklearn pipeline, Text-processing, Word2Vec, Gensim,*

Built a Sentiment analysis tool that classifies reviews to gain an overview of the customer's opinion in real-time. Applied text featurization techniques BOW, TFIDF, Word2Vec, Average Word2Vec, Tfidf weighted word2vec text featurization techniques, then trained various ML models. **Logistic Regression** with **TFIDF** Vectorization turns out to be the best model with AUROC of **0.982** with and **93**% accuracy.

-------

### [Quora Question Similarity](https://github.com/Skumarr53/Quora-Question-Similarity-Kaggle)

Topics: *Classification, sklearn pipeline, Text-processing, Word2Vec, Gensim, Spacy*

 Built a Classifier that identifies duplicate questions on Quora to enhance the user experience by instantly providing answers to questions that have already been answered. Created an NLP transformation pipeline for extracting basic, fuzzy, TFIDF, and Word2Vec features, then trained various ML models. **XGBoost** turns out to be the best model with **84**% accuracy.

-------
### [Netflix Recommendation: winners solution Implementation](https://github.com/Skumarr53/Netflix-Recommender-System)

Topics: *collaborative filtering, Surprise*

Built a recommendation system to make personal movie recommendations based on each customer’s unique tastes. Extracted basic features such as Global average of all movie ratings, Average rating per user, and Average rating per movie, top 5 similar users and movie ratings, and predictions from baseline models.  **XGBoost** turns out to be the best model with **0.967** rmse.

-------

### [Understanding PCA through image visualization](https://towardsdatascience.com/principal-component-analysis-in-depth-understanding-through-image-visualization-892922f77d9f)

Built a PCA model from scratch in Python, then tested on Multi-spectral satellite image data consisting of 7 band images. The first three Principal components retained **93**% information, thus original data was reduced from 7 dimensions to 3 without losing much information.

-------
## **Deep Learning**

### [Image Caption Generator](https://github.com/Skumarr53/Image-Caption-Generation-using-Fastai)

Topics: *PyTorch, Fastai, Caption Generation, Flask deployment, transfer learning, Encoder-Decoder, Beam search*

#### Demo:
![](https://raw.githubusercontent.com/Skumarr53/Image-Caption-Generation-using-Fastai/master/snapshots/caption_gen.gif)
<div style="text-align:center"><i>working App developed using Flask</i></div><br>

Implemented image caption generation method discussed **Show, Attend and Tell** paper using **Fastai** framework to describe the content of images. For encoder part, pre-trained **ResNet50** model is used and **LSTM** for decoder. Achieved **24** **BLEU** score for Beam search size of 5. Designed a Web application for model deployment using the **Flask** framework.

-------

### [Machine Translation - Transformer based](https://github.com/Skumarr53/Attention-is-All-you-Need-PyTorch)

Topics: *PyTorch, NLP, Fastai, Bert transformer, Encoder-Decoder, Streamlit*

* Implemented **Transformer** based machine translation method discussed in **Attention Is All You Need** paper using **Fastai** framework to translate queries French-to-English. Achieved **50** **BLEU** score using **BERT** architecture. Designed a Web application for model deployment using **Streamlit** framework.


--------

## **Web Development**

### [Building Portfolio website using Django - Heruko](https://skumar-djangoblog.herokuapp.com/blog/)
Topics: *Web-development, Django, Html, JQuery, Heroku*

**website link**: https://skumar-djangoblog.herokuapp.com/

* Developed a personal website using **Django** framework for sharing my ideas and projects. This website is hosted on **Heruko**.