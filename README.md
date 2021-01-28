# MoA-Kaggle

The challenge in this competition was to develop an algorithm to predict the Mechanism of Action of a drug compound given it's cellular and genetic expression. The dataset for this project was collected in collaboration between the Connectivity Map, a project within the Broad Institute of MIT and Harvard, Laboratory for Innovation Science at Harvard (LISH), and the NIH Common Funds Library of Integrated Network-Based Cellular Signatures (LINCS). It comprised of a training set of 23k+ examples with features such as genetic expression and cell viability in addition to information pertaining to treatment plan (dosage, duration etc.).

I approached the problem by breaking it down into multiple steps:
(1) Exploratory Data Analysis to identify collinearity between attributes
(2) Feature extraction (through FastICA) to extract the most informative feature set.
(3) Training a fully connected (3 hidden layers) neural network model with cross validation. 
(4) Prediction on test dataset.
