# **Multi-Layers Perceptron - Project**

Work done for the Spring 2020 class of Machine Learning with Python at ESA Master's degree. The instructor was Abdoul Aziz Ndoye.


# Instructions
Each group must report a file containing the sources and the code of the programs produced. The folder must contain a report and an analysis of the implementation of the methods developed. The project can be carried out under R, Python or SAS (You can use SAS Studio and the SAS Viya interface).

# Objective
he objective of this project is the implementation of a neural network in order to model the decision to grant credit. This modeling will be applied on the credit data (“credit_scoring”) which you will find in the repository with the description of the variables.  
These data consist of 1000 examples of credit applicants including 700 creditworthy. They have 21 variables describing the characteristics and personal information of each applicant, in particular:
— Le détail du compte courant,
— La durée du crédit, L’historique du credit, L’objet du crédit
— Le montant du crédit, Le compte épargne, le statut professionnel,
l’âge, le type logement
— ...

The idea will be to partition our database into two subsets. A learning set comprising 70% of the data (700 individuals) and a validation set including the rest (300 individuals), in a stratified way, that is to say that in the two subsets, the proportion of individuals having a default on the repayment of their loan is kept relative to the original population.

# Implementation
We build a MLP (Multi-Layers Perceptron) by choosing the architecture that best adapts to our data by determining the number of optimal hidden layer but also the number of neurons in each of these layers and the learning rate. It will therefore be a question of choosing several MLP with a different number of hidden layers (and neurons), benchmark them in order to have the best architecture possible. We will also discuss our choices according to the criteria used.

# Benchmarking
We will then assess the performance of our constructed neural network and compare our results to the performance of the following methods:
— Logistic Regression,
— Decision Trees,
— Random Forest,
— Gradient Boosting (XGBoost),
— SVC (Support Vector Classifier)


