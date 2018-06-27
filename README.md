# Drug-Activity-Prediction-Dorothea-Dataset
Python Program for Drug Activity Prediction using Dimensionality Reduction and Classification

### F1 Score: 0.7164
## Approach:
1.  The input sparse binary training data and testing data matrices were first expanded to full binary matrix of size 800 X 100000 and 350 X 100000 respectively.
2. The dimensions of both the matrices were then reduced from 100000 to 100 using Principal Component Analysis (PCA).
3. The test data was then classified using Bernoulli’s Naïve Bayes Classifier.
