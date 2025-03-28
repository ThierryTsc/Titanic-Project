🚢 Titanic - Predicting Survival with a Neural Network

This project applies a neural network to predict Titanic passengers' survival based on their characteristics. The goal is to explore the use of TensorFlow/Keras to solve a binary classification problem.



📂 Dataset
The dataset includes various passenger attributes, such as:

Survived: 0 = No, 1 = Yes (target variable)

Pclass: Ticket class (1st, 2nd, 3rd)

Sex: Passenger’s gender

Age: Passenger’s age

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Fare: Ticket price

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)




🛠 Technologies Used
Python

Pandas & NumPy (data preprocessing)

Scikit-learn (scaling and train/test split)

TensorFlow/Keras (neural network model)




🚀 Neural Network Model
The model is a fully connected neural network (MLP) with:

An input layer matching the dataset features

Two hidden layers with ReLU activation

A final output layer with sigmoid activation for binary classification

Adam optimizer and binary cross-entropy loss function




📊 Results
After training for 100 epochs, the model achieves approximately 92% accuracy on the test set.

💡 Potential Improvements
Hyperparameter tuning (number of layers, neurons, learning rate)

Regularization techniques (Dropout, Batch Normalization)

Comparison with other models (Logistic Regression, Random Forest, SVM)

