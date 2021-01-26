# Optical-Character-Recognition-via-Neural-Networks
The task for this exercise is to develop a Neural Network model that can classify human-written digits into either of the first 10.
1. Loading the MNIST digits dataset via sklearn provided built-in utility function(s).
2. Importing the necessary classes to do k-cross fold validation. You are free to choose k, depend- ing upon your computational budget and task complexity but for most purposes ’k=5’ suffices fine. Please set aside 20% of the images for testing.
3. Defining a hyperparameter grid for the ’MLPClassifier’ that is the Neural Network model imple- mentation from Sklearn. 
4. Defining a Random Search procedure over the ranges you chose above, and then train the model by calling the ’.fit’ method for the search object.
5. Reporting one test accuracy and the best hyperparameters found.
