Spam Classifier

A machine learning project to classify SMS messages as spam or ham (not spam) using text preprocessing, feature engineering, and supervised learning models.

Dataset : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

Features
	Loads and cleans the SMS Spam Collection dataset
	Text preprocessing:
	  •	Lowercasing
	  •	Tokenization (NLTK)
	  •	Stopword & punctuation removal
	  •	Stemming (PorterStemmer)
	Feature engineering:
	  •	Message length, word count, sentence count
	  •	TF-IDF vectorization of transformed text
	Visualization:
	  •	WordClouds for spam vs ham
	  •	Distribution plots for characters, words, and sentences
	Classification:
	  •	Trained using machine learning models (e.g., Naive Bayes, Logistic Regression, etc.)
	  •	Evaluated with metrics like accuracy, precision, recall, and F1-score
   
Tech Stack
	• Python (Pandas, NumPy, Matplotlib, Seaborn)
	• NLTK for text preprocessing
	• Scikit-learn for machine learning
	• WordCloud for visualization
 
Results
	• Achieved high classification accuracy (typically >95%)
	• Successfully detects spam messages with strong precision and recall


