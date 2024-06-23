# Sentiment-Analysis-NLP-project

Preprocessing Steps
1. Convert to lowercase: Standardizes the text for consistency.
2. Remove punctuation and numbers: Simplifies the text to contain only words.
3. Tokenization: Breaks text into individual words or tokens.
4. Remove stopwords: Eliminates common words that may not contribute to sentiment analysis.
5. Stemming: Reduces words to their base or root form.


Feature Extraction Techniques
TF-IDF
Weighs terms based on how unique they are, thereby highlighting important words in each document.

Bag of Words
Creates a simple representation of the text where each word is treated as a feature with its count in the text.

Models Used:
Logistic Regression
SVM
Random Forest
Gradient Boosting
Naïve Bayes
KNN
Decision Tree
Neural Network

Model Performance:
Highest Validation Accuracy: Logistic Regression achieved the highest validation accuracy of 89.5%. This model outperformed other models in accurately predicting the sentiment of movie reviews.
Lowest Performance Model: The K Nearest Neighbors (KNN) model showed the weakest performance among all the models tested of 56%. This indicates that KNN may not be the most suitable model for this text data analysis.

experimenting with various preprocessing techniques but no significant impact observed on the results.
We compared the Bag of Words approach with TF-IDF, which provided a slightly better accuracy, improving the results by approximately 2.5% compared to TF-IDF.

Results :
The analysis demonstrated that Logistic Regression provided the most reliable results in sentiment classification of movie reviews with Bag of Words slightly enhancing model accuracy. Future work could explore more advanced preprocessing techniques or hybrid models to further optimize performance.


DATA LINK:
https://www.cs.cornell.edu/people/pabo/movie-review-data/
