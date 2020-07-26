# Poker_Game_Visual_Machine_Learning

TO Run This Project.

1) you need to download the files

2)place all files in users folder

3)open anaconda

4)Run all the cells and you are ready to go.

------------------------------------------------------------------------------------


1)Introduction to the Project and Dataset

Import the dataset and then
to print the head of dataset

2)Separate the Data into Features and Targets
In this task, we will first manually label the columns and classes based on the dataset description from the UCI Repository.

Finally, we’ll separate the data into features X and targets y for further analysis.


3)Evaluating Class Balance


4)Up-sampling from Minority Classes

5)Training a Random Forests Classifier
Now we’ll partition our poker hand data into training and test splits, 
so that we evaluate our fitted model on data that it wasn’t trained on.
 This will allow us to see how well our random forests model is balancing the bias/variance trade-off.

6)Classification Accuracy
In this short task, we will compute the classification accuracy score of our random forests model on the test data.

7)ROC Curve and AUC
Now that our model is fitted,
 we evaluate its performance using some of Yellowbrick’s 
visualizers for classification. With Yellowbrick’s implementation of ROCAUC we can evaluate a multi-class classifier.
 Yellowbrick does this by plotting the ROCAUC curve for each class as though it were it’s own binary classifier, all on one plot.

8) Classification Report Heatmap

The classification report displays the precision, recall,
 and F1 scores for the model. In order to support easier interpretation and problem detection,
 Yellowbrick’s implementation of ClassificationReport integrates numerical scores with a color-coded heatmap.

The classification report shows a representation of the main classification metrics on a per-class basis. 
This gives a deeper intuition of the classifier behavior over global accuracy which can mask functional weaknesses in one class of a multiclass problem.

9) Class Prediction Error
The Yellowbrick Class Prediction Error chart shows
 the support for each class in the fitted classification model 
displayed as a stacked bar. Each bar is segmented to show the distribution 
of predicted classes for each class. It is initialized with a fitted model and generates a class prediction error chart on draw. For my part, 
I find ClassPredictionError a convenient and easier-to-interpret alternative to the standard confusion matrix.



