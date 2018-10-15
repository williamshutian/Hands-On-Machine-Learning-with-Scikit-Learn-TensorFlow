1. Visualize the data (scatterplot)
    * See density by alpha
    * Use color map(option cmap) called jet

2. Compute the standard correlation coefficient(-1 to 1)
                   「corr_matrix. Or. pandas’ scatter_matrix」

3. Experiment with attribute combinations

Prepare the data 
* Data cleaning
    * take care of the missing features 「imputer」
* Handing Text and Categorical Attributes
    * Transformer the text 「LabelEncoder」 1D array
    * OneHotencode() to array 2D array
    * Combine above approach use「LabelBinarizer」 2D array
* Custom Transformers
    * For combined specific attributes
* Features Scaling
    * Min-max scaling
    * Standardization
* Transformation Pipelines

Select and train a model
* Train and evaluating on the training set
    * Train in linear model
    * Measure the RMSE
    * Fix Underfitting : 
        * Select more powerful model
        * Feed the training algorithm with better features
        * Reduce the constrains on the model
    * Try decision tree model (can fix nonlinear relationships of data)
* Better evaluation using cross-validation
    * Use k-foldcross-validation
    * Use random forest (train many decision tree on random subsets of the features then average out their predictions )
    * Fix Overfitting :
        * Simplify the model
        * Constrain the model
        * Get a lot more training data

Fine-Tune the model
* Grid search
    * Use GridSearchCV to deal with the hyper-parameter
* Randomized search
    * Hyperparameters search space is large
    * Benefits :
        * More iterations will explore more different values for each hyper-parameter
        * Have more control over the computing budget
* Ensemble methods
* Analyze the best models and their error
* Evaluate your system on the test set
