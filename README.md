# MoA-Kaggle

The challenge in this competition was to develop a predictive algorithm that takes as input treatment plans, cellular and genetic information for 5000+ drug compounds and predicts the mechanism of action of these drugs. 

I worked on this project by breaking it down into several steps: 
1. Exploratory Data Analysis: This helped me familiarize myself with the dataset and understand which features were correlated and how much redundancy existed in the dataset.
2. Feature Extraction: Genetic information and cellular information is a result of mixing at a physiological level. To unmix and identify the most important features, I used Independent Component Analysis. 
3. Model Generation: I used a neural network model to generate predictions. The model is three layer deep and incorporates dropout regularization, k-fold cross validation and early stopping to prevent model overfitting. The model was trained on Kaggle provided GPU. 
4. Evaluation: The model was evaluated using a custom metric provided by the competition administration (my model scored a loss of 0.01678 compared to the winning model score of 0.01599).

![Summary](https://github.com/smallik92/MoA-Kaggle/blob/main/Figure%204.png)
