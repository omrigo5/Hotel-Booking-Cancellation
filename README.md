# Hotel-Booking-Cancellation
Goal: Predict the chances of hotel reservation cancelation using data of costumers from multiple hotels. The data is given in a tabular form of 32 columns (20 numerical + 12 objects), and taken from Kaggle datasets: https://www.kaggle.com/jessemostipak/hotel-booking-demand

As a first stage the data was seperated into training/validation/test sets. To get the optimal model I have investigated the features in the training-set, starting with the numerical features that are most correlated with the target. I proceded with encoding the categorical features while monitoring the accuracy with a small subset of features to get an initial estimation of the achievable prediction.

Model selection was made by considering 3 models (Random Forest, Gradient Boosting and Logistic Regression) and evaluating them on the validation set. The effectiveness of dimensionality-reduction (using PCA) and model tuning (using Grid-Search) was assessed as well.
