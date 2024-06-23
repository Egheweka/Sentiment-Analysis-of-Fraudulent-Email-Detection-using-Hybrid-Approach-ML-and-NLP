# Email Sentiment Analysis for Fraudulent Email Detection

Email sentiment analysis has become an important area of research due to the increasing volume of email communication across various industries. Understanding the sentiment expressed in emails can provide insights into customer satisfaction, employee morale, and other factors critical to business success. This study focuses on developing a model to classify emails into positive, negative, or neutral categories using both lexicon-based and machine learning approaches.

**Introduction**
Sentiment analysis involves using natural language processing (NLP) techniques to extract meaning and sentiment from text. For fraudulent emails, this involves analyzing the language used in the email to determine whether it conveys positive or negative sentiment toward the fraudulent activity. This analysis is crucial for identifying potential scams and protecting individuals and organizations from financial loss and other negative consequences. By accurately identifying the sentiment in these emails, organizations can take proactive steps to prevent fraud and protect themselves and their customers.

**Objectives**
The primary aim of this study is to perform sentiment analysis on fraudulent emails, identify the sentiments behind such emails, and model their outcomes. The key objectives include:
•	Classifying emails into positive, negative, or neutral sentiment categories.
•	Comparing the performance of different machine learning models in sentiment classification.
•	Evaluating the effectiveness of various sampling techniques in improving model performance.

**Methodology**
1.	**Data Collection:**
o	A total of 14,472 emails were used, extracted from the Enron Corporation dataset and Kaggle dataset.
2.	**Data Preprocessing:**
o	Techniques such as stop word removal and stemming were applied to facilitate analysis.
3.	**Sentiment Analysis Approaches:**
o	**Lexicon-based Approach**: Classifies emails into negative, neutral, and positive sentiments.
o	**Machine Learning Models:** Four models were compared based on performance metrics:
	Random Forest
	K-Nearest Neighbors (KNN)
	Support Vector Machine (SVM)
	Logistic Regression
4.	**Performance Metrics:**
o	Models were evaluated based on precision, recall, F1-score, and accuracy.
5.	**Sampling Techniques:**
o	Different sampling techniques were tested, with the SMOTEENN technique producing the best results.

**Results**
•	**Lexicon-based Approach:**
o	Enron Dataset: Negative (8%), Neutral (34%), Positive (59%)
o	Kaggle Dataset: Negative (18%), Neutral (23%), Positive (60%)
o	Combined Dataset: Negative (9%), Neutral (32%), Positive (59%)
•	**Machine Learning Models Performance:**
o	**Support Vector Machine (SVM)** had the best predictive performance with the combined dataset:
	Precision: 91%
	Recall: 76%
	F1-score: 79%
	Accuracy: 88.29%

**Discussion**
The study demonstrates the practical implications of utilizing machine learning algorithms and appropriate sampling techniques to detect and prevent fraudulent emails. The findings highlight that employing advanced models like SVM, along with effective sampling methods like SMOTEENN, can significantly enhance the detection of fraudulent emails and help organizations avoid financial losses.

**Conclusion**
This study emphasizes the importance of continuous improvement and testing of algorithms to ensure they remain effective in detecting evolving types of fraudulent emails. By integrating both lexicon-based and machine learning approaches, organizations can achieve a more robust and accurate sentiment analysis system, leading to better fraud prevention strategies.

**Datasets**
The datasets can be downloaded from the following links:
•	Enron Corporation dataset
•	Kaggle Fraudulent Email Corpus

