# KRW_assign1
KR_web

README
This repository contains files for a project on the analysis of opioid data. Below are instructions on how to clone the git and descriptions of each file.

How to Clone
To clone this git, follow these steps:

Open your terminal.
Navigate to the directory where you want to clone the git.
Type git clone https://github.com/agnesadm1997/KRW_assign1.git.
Press enter.
Files
data_cleaning.ipynb
This file cleans the opioid_data_original_xlxs dataset and merges it with another dataset, sider_output.xlxl. The cleaned data is merged into one file.

ontology_medsur.ipynb
This file builds an ontology from the dataset and exports all the generated triples as a csv ttl and rdf file.

clustering_chars.ipynb and clustering_symps.ipynb
Both files are in the folder clustering and perform clustering machine learning on the dataset medsur.csv. They cluster on patient characteristics and patient symptoms using the ampligraph model.

link_prediction.ipynb
This file performs 4 link predictions:

Outcome recovery for different weight groups of patients.
Outcome recovery for different age groups of patients.
Symptoms for different types of prescribed drugs.
Side-effect occurrence for different types of prescribed drugs.
For each prediction, a csv file is exported containing the prediction scores and probabilities for each group or drug type.

This file contains two important functions that may need some extra explanation:

build_model(X_train, X_test, model = 'ComplEx', epochs = 1)
This function builds a ComplEx model on the given dataset. It takes in three parameters:

X_train: the training set.
X_test: the testing set.
model: the model type. Default is ComplEx.
epochs: the number of epochs to train for. Default is 1.
This function returns the built model.

link_prediction(model, df, cluster, predicate_link, X_training, X_testing, trip)
This function predicts the probability of a (predicate) link between a cluster of patients and all possible outcomes. It takes in seven parameters:

model: the trained model.
df: the dataframe of all triples.
cluster: the cluster of patients.
predicate_link: the predicate link to predict.
X_training: the training set.
X_testing: the testing set.
trip: the triple factory.
This function returns two dataframes: df_ranking and df_results.
