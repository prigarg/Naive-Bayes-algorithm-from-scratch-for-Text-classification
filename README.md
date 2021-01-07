# Naive-Bayes-algorithm-for-Text-classification
Naïve Bayes Algorithm is implemented in order to classify spam and not spam emails.

#### Dataset.zip : Dataset contains training and test set. Each set consists of spam and ham directories. All the files in spam set are spam emails and files in ham set are non-spam emails.

The implemented algorithm uses add-one smoothing. The algorithm is also improved using two follwing approaches:
1) `Filtering the Stop Words` - The list of stop words is in `stopwords.txt`.
2) `Feature Selection` - select various top % of features (words) from the dictionary in training dataset seperatley for spam and ham. 

In the end accuracy for test data is shown for general naive bayes implementation, naive bayes after removing stop words and naive bayes for feature selection (10%, 20%,..., 100%). The results are comapred and visulaized through graaphs for checking how accuracy improves.

** Please remember to change the file location in the program to load the corpus for spam and ham in `test_spam`, `test_ham`, `train_spam`, `train_ham`.
