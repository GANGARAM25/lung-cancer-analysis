# lung-cancer-analysis
Unsupervised Learning and supervised Learning on dataset of lung cancer analysis

# Question 1: Unsupervised Learning
1) Apply PCA (select number of components by preserving 95% of total variance). (in-built
function allowed for PCA).
2) Plot the graph for PCA.
3) Using the features extracted from PCA, apply K-Means Clustering. Vary the value of K from 2
to 8. Plot the graph of K vs normalised mutual information (NMI). Report the value of K for
which the NMI is maximum. (in-built function not allowed for K-Means).
4) Prepare a report including all your results

# Supervised Learning (70)
1) Normalise the data using Standard Scalar Normalisation. Randomly divide the Dataset into
80% for training and 20% for testing. Encode categorical variables using appropriate
encoding method (in-built function not allowed for normalization, sampling and
encoding).
2) Implement the binary SVM classifier using the following kernels: Linear, Quadratic, Radial
Basis function. Report the accuracy for each. (in-built function allowed).
3) Build an MLP classifier (in-built function allowed). for the given dataset. Use stochastic
gradient descent optimiser. Keep learning rate as 0.001 and batch size of 32. Vary the
number of hidden layers and number of nodes in each hidden layer as follows and report the
accuracy of each:
a. 1 hidden layer with 16 nodes
b. 2 hidden layers with 256 and 16 nodes respectively.
4) Using the best accuracy model from part 3, vary the learning rate as 0.1, 0.01, 0.001, 0.0001
and 0.00001. Plot the learning rate vs accuracy graph.
5) Use forward selection method on the best model found in part 3 to select the best set of
features. Print the features.
6) Apply ensemble learning (max voting technique) using SVM with quadratic, SVM with radial
basis function and the best accuracy model from part 3. Report the accuracy.
7) Prepare a report including all your results.
