Classification

MINIST
* Shuffling the dataset to avoid many similar instance in a row and guarantee that all cross-validation folds will be similar

Training a Binary Classifier (Support Vector Machine classifiers and Linear classifiers)
* Stochastic Gradient Descent
    * Handling very large datasets efficiently
    * Deal with training instances independently, one at a time (suited for online learning)

Performance Measures
* Measuring Accuracy Using Cross-Validation
* Confusion Matrix
    * Get a clean prediction for each instance in the training set
    * Negative class[true negative, false positive]
    * Positive class[false negative, true positive ]
    * 
    * TP is the number of true positive, and FP is the number of false positive
    * 
    * FN is the number of false negative
    * 
* Precision and Recall
    * 
    * Precision/recall tradeoff: increasing precision reduces recall and vice versa
* Precision/recall tradeoff
    * 
    * Raising threshold decrease recall
* The ROC Curve
    * TNR = TN / (TN + FP)
    * 

Train binary classifiers: choose the appropriate metric for the task, evaluate the classifiers using cross-validation and select the precision/recall tradeoff that fit the need, compare various models using ROC curves and ROC AUC scores.

Multiclass Classification:
Can distinguish more than two classes
(Random Forest classifiers and naive Bayes classifiers)
OvA
OvO : train N*(N-1)/2 classifiers
          Each classifier only needs to be trained on the part of the training set                       for the two classes that it must distinguish

True project:


Error Analysis:
* Divide each value in the confusion matrix by the number of images in the corresponding class
* Fill the diagonal with zeros to keep only the errors

Multipliable Classification
Multiclass for each instance

Multioutput Classification:
Each label can be multiclass (more than two values)
KNeighborClassifier.fit(x,y) means fit x to y

