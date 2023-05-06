# Corona-Tweet-Sentiment-Analysis
# Project Summary
Sentiment Analysis is a process of computationally determining the underlying sentiment from the piece of textual information. Sentiment Analysis is widely used in different industries to understand customers' opinions about the firm's activities, such as product launches, marketing campaigns, etc. In this project, we are doing sentiment analysis on coronavirus tweets for one month.

In this project, the dataset contains six features and  41157 observations. The dependent variable is the sentiment column with values such as Extremely Positive, Positive, Neutral, Negative, and Extremely Negative. The dependent column is the Original Tweet column, whereas other features don't have much importance for the analysis.

The different steps involved in this sentiment analysis project are,
Exploratory Data Analysis
Text Preprocessing
* Tokenization
* Removing patterns, stop words, and punctuation
* Normalization
* Vectorization
* Data Splitting
* Data Scaling
* Model Implementation



---


**Exploratory Data Analysis**
 	In EDA, we will deal with the missing and duplicates in the dataset. We look deeper into the variables and their relationships with each other.


---



**Text Preprocessing**
* **Tokenization** - Tokenization is the first step in any Natural Language Processing Project. It is the process of converting unstructured data into chunks.
* **Removing patterns, stop words & punctuations** - Removing stopwords and punctuation is the next step. We don't need a Twitter user handle in the original tweet column in sentiment classification. So, we remove all the unwanted information through regular expressions in python.
* **Normalization** - Normalization in NLP is converting the words to their base words. There are two different types of normalization, namely stemming and lemmatization.
* **Vectorization** - Vectorization is the step where all the words get converted into numbers. Because machine learning algorithms don't understand text data. There are different types of vectorizers such as Count Vectorizer, Tfidf, ngrams, word embedding, word2vec, etc.,
---
**Data Splitting**

In data splitting, we split the dataset into training data and testing data on a chosen ratio. The training data is applied to train the machine learning models, and test data is employed to check the performance of the data over unseen test data.

---

**Model Implementation**

In this project, we use machine-learning models such as Logistic Regression, Random Forest Classifiers, Support Vector Classifiers, Decision Tree Classifiers, and SGD Classifiers.

---


