# Author-Identification

The problem of author identification in this project can be clearly stated in "Given Text, identify who is the author of that text" which is considered a multiclass classification problem.
The dataset in this project contained 50 classes of authors for train and test data each of which has a total of 50 observations.
I performed exploratory data analysis to have a good understanding of our data to make a better decision when choosing the input features. I also stemmed and lemmatized our data.
For the models, I applied Multinomial Naïve Bayes, Support Vector Machine, Random Forest, and Logistic Regression on the clean, lemmatized, and stemmed data along with the comparison of the performance. I found out that logistic regression performed the best when using the TFIDF representations on all the datasets.
I compared the performance of TFIDF with Glove Pre-trained embedding on the dataset. The results showed that the TFIDF performed better compared to the pre-trained Glove embeddings on the traditional machine learning model.
When using pre-trained word embeddings on traditional machine learning algorithms, I were required to average word vectors which result in loss of information and this is the reason of having low scores with them.
Even though the dataset was balanced, but for 50 classes, the data was very less. Having more observations would be made the models perform better, but at the same time, it is very difficult.
