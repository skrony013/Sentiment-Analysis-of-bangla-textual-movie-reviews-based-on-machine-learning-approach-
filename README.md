# Sentiment-Analysis-of-bangla-textual-movie-reviews-based-on-machine-learning-approach.

Md. Rony Shaikh
Department of Computer Science & Engineering
BSMRSTU. 

# Introduction
With the appearance of social networking and internet, Sentiment Analysis is getting one of the most significant research regions for prediction and classification. The analysis of the each single textual movie review in manual mode is complicated and exhausting. An automated system can release us from such type of complication. Hence we proposed an automated system called Sentiment Analysis (SA) that is the technique of extracting opinions, emotions from textual data in Bangla language to develop such a system.

# Objective

1. To provide a classification model that can automatically classify text into positive or negative. 
2. To evaluate the audience feedback in certain movies. 
3. To inform the audience about the film whether they watch the movie or not. 
4. To achieve better accuracy than previous work. 

# Data Preprocessing
The first part of the project is data-preprocessing. Since the original dataset contains only raw text with its label, we need to transform the shape of natural language and remove noises in order to better fit our model. Therefore, the data preprocessing part contains the following steps:
1. Tokenization
2. Punctuation and emojis removal
3. Stopword removal 
4. Stemming 
5. Normalization

Besides, for the purpose of contrasting with traditional NLP classification methods, it is also essential to vectorize phrases (TF-IDF, Count Vectorizer) in order to learn the correlation between texts rather than treating words as discrete symbols like the bag of words model. 

# Feature Selection
1. TF-IDF
2. Count Vectorizer 

# Description of Dataset 

The dataset used in this experiment was collected manually from the comments of people on social networking websites such as Facebook, YouTube, BMDB website etc. In this dataset, it has one feature as 'Review' and one class label as 'Sentiment'. It contains around 5000 samples, each labeled as either positive or negative. The Dataset consists of 2,600 positive reviews marked by 1 and 2,400 negative reviews marked by 0.  Due to the fewer amounts of data, further classification of the positive and negative classes was not possible using this particular dataset. 80% of the data was used for training and the remaining 20% was used as the test set. For validating the performance even further, Kfold cross-validation was performed. 

# Models 

1. Decision Tree
2. Random Forest
3. Naive Bayes
4. GBM
5. ANN

By analyzing the results, it can be interpreted that Random Forest Classifier performed better than other approaches. This model also obtained decent accuracy(92.23%).
 


