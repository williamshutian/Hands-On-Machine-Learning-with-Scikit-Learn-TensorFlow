
Machine learning is about making machine get better at some task by learning from data without explicitly programmed.

Supervised learning: the training data you feed to the algorithm includes the desired solutions
Task is classification and predict a target numeric value, regression.

Supervised learning algorithm:   
* k-Nearest Neighbors
* Linear Regression
* Logistic Regression
* Support Vector Machines (SVMS)
* Decision Trees and Random Forests
* Neural Network

Unsupervised learning: the training data is unlabeled, the system tries to learn without a teacher. 
Task is dimensionality reduction, anomaly detection and association rule learning.

Unsupervised learning algorithms: 
Clustering
* K-Means
* Hierarchical Cluster Analysis (HCA)
* Expectation Maximization
Visualization and dimensionality reduction
* Principal Component Analysis (PCA)
* Kernel PCA
* Locally-Linear Embedding (LLE)
* t-distributed Stochastic Neighbor Embedding (t-SNE)
Association rule learning
* Apriori
* Eclat

Semisupervised learning: some algorithms deals with partially training data, usually a lot of unlabeled data and a little bit of labeled data.

Reinforcement Learning: observe the environment, select and perform actions, and get rewards in return.

Batch learning: must be trained using all available data, offline learning.
(A lot of time and computing resources)

Online learning: train the system incrementally by feeding it data instances sequentially, either individually or by small groups called mini-batches.
(Save space)
Out-of-core learning: train systems on huge datasets that cannot fit in one machine’s main memory. The algorithms loads part of the data, runs a training step on that data and repeats the process until it has run on all of the data.

Two approach to generalization: instance-based learning and model-based learning.

Instance-based learning: system learns the examples by heart, then generalizes to new cases using a similarity measure.

Model-based learning: build a model of these examples, then use that model to make predictions.

Machine learning project:
1. Study the data
2. Select a model
3. Train it on the training data
4. Apply the model to make predictions on new cases

Main challenges of machine learning:
Bad data:
* Insufficient quantity of training data
* Non representative training data
* Poor-quality data
* Irrelevant features
Bad algorithm:
* Overfitting the training data
* Under-fitting the training data

Cross-validation: the training set is split into complementary subsets, and each model is trained against a different combination of these subsets and validated against the remaining parts.


