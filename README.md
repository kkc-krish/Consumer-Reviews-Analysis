# Consumer-Reviews-Analysis

Model Building Notes: 

Tools Used: Python programming using Anaconda IDE 

Python Packages: Os, Pandas, Sklearn, Numpy, Matlplotlib, Seaborn, NLTK, Statsmodels.api, Pylab, SpaCy, Gensim, PyLDAvis 

Key assumption is to reflect the overall sentiment using Information extraction on reviews dictionaries. We are not attempting at single product aspect entity relations (Single product feature extraction, given the time constraint and the requirement to build a large pre-trained data set) 

Models not attempted as part of solutions, considering them not required as part of our problem case: Sentiment Classifier, Ratings based analysis - Classifying products based on ratings, calculating mean rating scores of products 

Data Modelling Approach -Assumptions and comments mentioned in Ipython NoteBook 
Data-set source link: https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products

Problem Statement: Understanding insights from Customer Reviews - identify key product terms in the sentiments (Topic Modelling) - do sentiment analysis (classify sentiments - for future use cases) - understand product wise sentiments (Data Modeller Understanding of the problem) 

Different types of NLP analysis which can be employed for our use: Given that we are dealing with Reviews, (Textual Data - Applications of NLP Techniques), following sub analysis - 
1. Entity Recognition (Named Entity Recognition), 2. Identifying Emerging Trends 3.Sentiment Analysis  4. Text Summarization 5. Topic Modelling 
and solutions deduced can be applied as a universal attempt for exploring the data. 

We will restrict ourselves to Sentiment Analysis & Topic Modelling and explore advanced enhancements at later when we deploy real time sentiment monitors - probably by streaming data analysis using Databricks/ Apache Spark 

Model - 1  : 

Problem statement Scope and Topic Modelling: 
By the nature of unstructured Textual data, we want to derive insights about sentiments of consumers in terms of product features - authenticity of the product, quality of the product and from consumer standpoint, our support engine should be able to redflag fake reviews. Topic Modelling is a process to automatically identify topics present in a text object and to derive hidden patterns exhibited by a text corpus, thus assisting in better decision making. 

Model -2: Aspect Based Sentiment Analysis also known as Feature Based Sentiment Analysis is a technique to find out various features, attributes, or aspects from a given text and their respective sentiments. 


Refer to Model-1 for Topic Modelling and LDA Analysis 
Refer to Model-2 for Aspect Based Sentiment Analysis 

Please download Modelling Notes Document for Problem Approach - output previews and analysis 

Additional Model - Sentiment Classifier: 

Sentiment analysis is the process of detecting positive or negative sentiment in text. 
We will build classification algorithms to detect the text 

We built Logistic regression and Random forests for sentiment classification as positive or negative reviews 

Additional Coding references - websites index: 
Github 
Stackexchange 
Paperswithcode 
Medium  and towardsdatascience 
Analytics Vidhya 
