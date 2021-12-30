# Iris Flower Dataset Assignment

**Preparing The Data:**  
    * First of all, we loaded the Iris dataset from the scikit-learn library.  
    * We printed the dataset, feature names & labels (target names).  
    * We split the data (features, labels) into 70% training, 30% testing.  

**Decision Tree Algorithm:**  
    * We defined a decision tree classifier.  
    * We trained the model using 'fit' function on the 70% data we put aside for training.  
    * We tested the X_test data we put aside for testing, using 'predict' function & got predict_dt.  
    * We checked the accuracy of our results against the y_test data we put aside - multiplied by 100 to get %,
      and got accuracy of approx. 95%.  
    * We visualized the decision tree.  

**KNN Algorithm:**  
    * We scaled down the 70% feature data (X_train, X_test), so we'll have all data in range.  
       That is needed in KNN algorithm, because it's training relays on minimum distance from specific point in range.  
    * We defined a KNN classifier.  
    * We trained the model using 'fit' function on the 70% scaled down features data and 70% labels data for training.  
    * We gave a default n_neighbors = 5 that gives higher accuracy results.  
    * We tested the X_test scaled down data using 'predict' function & got predict_knn.   
    * We checked the accuracy of our results against the y_test data we put aside - multiplied by 100 to get %,
      and got accuracy of approx. 97%.  
      
**Conclusion**  
    * Classification - a type of supervised ML problem where the target variable is categorical.   
        Given a training data that contains a known label, the classifier maps from the input to output variables.   
    * There are a number of ways to classify the Iris Flower data set, but I chose to learn Decision Tree and KNN  
       that are both supervised ML algorithms.   
    * Decision Tree - builds a classification model on the training dataset before being able to actually classify   
       an observation from test dataset. Then the model is able to classify unseen training instances (observations).        
    * KNN - directly learns from the observations. It starts processing data after it is given  
       a test observation to classify. It is not recommended to use when there's a large number of features.  
    * There are other supervised algorithms we could have used for classification, such as:  
       Naive Bayes, LDA, QDA, SVG.  
