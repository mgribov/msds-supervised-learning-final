# Predicting Wine Quality From Chemical Composition

Video of the presentation: https://youtu.be/BZMT3t53mAc

The goal of this project is to attempt to predict quality of wine based on its chemical properties.

The project uses the [Wine Quality](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) dataset, publicly available from the [UCI ML data repository](https://archive.ics.uci.edu/ml/datasets.php).

The dataset contains chemical properties and associated quality scores for red and white variants of Portuguese "Vinho Verde" wine. 

The scores range from 1 to 9, and come from human tasters as part of the wine certification process to ensure quality and safety of the wine, and can also be used to refine wine making process and to stratify wines into premium brands.

The dataset is accompanied by a paper, ["Modeling wine preferences by data mining from physicochemical properties"](http://dx.doi.org/10.1016/j.dss.2009.05.016) by P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis, which approaches the task as a regression problem to predict the scores, but I will instead approach it as a classification problem, and instead attempt to predict if a given wine is "great" or just "regular".

To accomplish this, I will transform the quality score into a binary (0/1) class, signifying a "regular" or "great" wine based on the score ranges, and then train various classification algorithms to predict whether a wine will be "great".

Specific classification algorithms evaluated:
* K-Nearest Neighbors
* Random Forest Classifier
* Support Vector Classifier
* Multi-layer Perceptron

Full analysis notebook is here: [Predicting Wine Quality of White Variant of Vinho Verde.ipynb](Predicting%20Wine%20Quality%20of%20White%20Variant%20of%20Vinho%20Verde.ipynb)

