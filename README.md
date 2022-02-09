# Machine Learning Engineer Nanodegree
## Project: Capstone Proposal and Capstone Project

**Note**

The file "Text_Classification.ipynb" contains all the python code used for this projects.

The explanation for the main sections in the file are as follows:

1. Importing Libraries
- This section imports all the libraries required for this projects

2. Fetching Data and Tokenizing
- This section fetches the train and test data from sklearn datasets
- This section also contain the tokenizer I implemented to tokenize words into lowercase and remove stopwords

3. Classification
- This section contains pipelines for three different classifiers based on tf-idf vectors.

4. Parameter tuning using Grid Search
- This section contains parameter tuning that was performed on naive bayes and svm to find base parameters for both

5. Implementing Doc2vec
- This section contains the approach use for training vectors on Doc2Vec model, inferring test vectors from the model and then using the trained vectors as inputs into svm classifier.

6. Evaluating classifiers
- This section compared the classifiers in terms of their accuracy and f1 scores

7. Evaluation of final model
- This section evaluated final model for its metrics

8. Testing model on unseen data
- This section is used for testing the model on new unseen data (new sentences)
