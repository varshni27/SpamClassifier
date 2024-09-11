# Spam vs Ham Classification
This project classifies SMS messages as spam or ham (not spam) using a Naive Bayes classifier. The dataset contains 5,572 messages labeled as either spam or ham, and the model is trained to predict the class based on message content.

## Steps

### Exploratory Data Analysis:
- Visualized the distribution of ham vs spam using Seaborn's countplot.
- Created word clouds for both spam and ham messages to analyze frequently used words.

### Modeling:
- Split the data into training (75%) and testing (25%) sets.
- Used TfidfVectorizer to transform text data into numerical features.
- Trained a Naive Bayes classifier to classify messages.

### Results:
- Achieved an accuracy of 96.6% on the test set.
- Measured performance metrics: confusion matrix, precision, recall, and F1-score.

### Libraries Used:
- pandas, numpy for data handling.
- matplotlib, seaborn for visualization.
- wordcloud for generating word clouds.
- scikit-learn for model training and evaluation.

### Conclusion:
The Naive Bayes model performs well in identifying spam messages with high accuracy.
