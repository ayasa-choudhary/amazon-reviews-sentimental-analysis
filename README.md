Amazon Reviews Sentiment Analysis

This project focuses on performing sentiment analysis on Amazon product reviews using Python and key data science libraries. The goal is to classify reviews into positive or negative sentiments, enabling insights into customer feedback trends.

Key Features:
	1.	Data Preprocessing:
	•	Utilized numpy and pandas for data cleaning, manipulation, and exploratory analysis.
	•	Handled text data effectively by transforming the Review column into feature vectors.
	2.	Visualization:
	•	Created word clouds with the wordcloud library to visualize the most frequent terms in positive and negative reviews.
	•	Applied matplotlib and seaborn for detailed data visualizations, enhancing interpretability.
	3.	Feature Extraction:
	•	Employed sklearn.feature_extraction.text for converting text data into numerical representations using techniques like TF-IDF.
	4.	Model Training and Testing:
	•	Built and trained a logistic regression model using the sklearn library.
	•	Split the dataset into training and testing subsets, achieving an accuracy score of 81.45% on the test set.
	5.	Evaluation:
	•	Generated a confusion matrix to evaluate the model’s performance in terms of true positives, true negatives, false positives, and false negatives.
	•	Visualized the confusion matrix using ConfusionMatrixDisplay.

Results:
	•	The project successfully demonstrates the ability to predict the sentiment of Amazon reviews with high accuracy.
	•	The word cloud visualizations provide valuable insights into commonly used terms in different sentiments.

Libraries Used:
	•	numpy, pandas, matplotlib, seaborn
	•	sklearn (for feature extraction, model training, and evaluation)
	•	wordcloud
