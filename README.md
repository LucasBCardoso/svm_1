# INTRODUCTION TO DEEP LEARNING - TASK 2:

The Heart.csv file presents the clinical data of patients along with the
record of the existence or not of heart disease (column AHD). Using an SVM,
the task is to predict whether a patient has heart disease or not from the
clinical data (binary classification). To do this, follow these steps:

Split the data into training and testing (70-30) keeping both sets approximately
balanced. Discard entries with missing information (NA).

Select 2 features from the 13 available.
Plot the training and testing sets using the chosen variables.
Use the training set to fit an SVM with linear, polynomial, and radial kernels.

Adjust the hyperparameters accordingly.
Plot the maximum margin [2] of the training set for each kernel.
Plot the regions and decision boundaries [3] of the training set for each kernel.

Estimate the heart disease (AHD) on the test set and calculate the accuracy
(percentage of success) for each kernel.

Present the plots of the regions and decision boundaries of the test set for
each kernel.

OPTIONAL: Define a new SVM model using all the features, repeat the estimation
on the test set, and check if the accuracy has improved.