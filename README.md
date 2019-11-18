# Naive Bayes Classifier
## Sentiment Analysis on Emails

The data has been already split into two subsets: a 3200-email subset for training and a 800-email subset for testing (consider this as your validation set and imagine there is another test set which is not given to you). Features have been generated for you. You will use the following files:
• question-4-train-features.csv • question-4-train-labels.csv
• question-4-test-features.csv • question-4-test-labels.csv
• question-4-vocab.txt
The files that end with features.csv contain the features and the files ending with labels.csv contain
the ground truth labels.
In the feature files each row contains the feature vector for an email. The j-th term in a row i is the occurrence information of the j-th vocabulary word in the i-th email. The size of the vocabulary is 37358. The label files include the ground truth label for the corresponding email (label 0 is medicine, label 1 is space, label 2 is cryptology and label 3 is electronics), the order of the emails (rows) are the same as the features file. That is the i-th row in the files corresponds to the same email. Each email is labeled as either cryptology, space, medicine or electronics.
The file ending with vocab.txt is the vocabulary file in which the j-th word (feature) in the file corresponds to the j-th feature in both train and test sets.

**The data files can be found in the following link:** https://drive.google.com/open?id=1Uq9pw49c9SN28iF07hMvV541v6rzw0dP
## Predictions and Types in the Program
There are two type of multinomial naive bayes classifier in this implementation. One of them with maximum likelihood estimator and the other one is maximum a posterior. There are different accuricies for each implementation.

### Prediction Accuracy with MLE: 26%
### Prediction Accuracy with MAP: 93%



