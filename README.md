# CS123A-Project-Classification of Mushrooms and Beans
##  Project Overview
This project explores machine learning classification using two biological datasets from the UCI Machine Learning Repository. We use a Random Forest classifier to learn patterns from the features of each dataset and predict the correct class for new samples.
##  Dataset 1: Mushroom Dataset
The Mushroom Dataset contains **8,124 samples** and **22 original features.**

The features describe different characteristics of mushrooms, such as:

- Cap shape
- Cap surface
- Cap color
- Odor
- Gill size
- Stalk characteristics
- Habitat
- Population
  
The target variable identifies whether the mushroom is:
- Edible
- Poisonous

##  Dataset 2: Dry Bean Dataset
The Dry Bean Dataset contains **13,611 samples** and **16 numerical features**.

The features mainly describe the physical size and shape of each bean, including:
- Area
- Perimeter
- Major Axis Length
- Minor Axis Length
- Aspect Ratio
- Eccentricity
- Roundness
- Compactness

The target variable is the bean variety.

##  Method
We use a **Random Forest Classifier** for both datasets.

The datasets are split into:
- 80% training data
- 20% testing data

For the Mushroom Dataset, one-hot encoding is used to convert categorical features into numerical features before training.

The Random Forest model uses:
- 100 decision trees
- Random state of 23

##  Conclusion
This project demonstrates how Random Forest classification can be applied to two different biological datasets.
The Mushroom Dataset represents a binary classification problem using mainly categorical features, while the Dry Bean Dataset represents a multiclass classification problem using numerical physical measurements.

Using both datasets allows us to explore how the same machine learning method can be applied to different types of biological classification problems.

##  Tools and Libraries
- Python
- Google Colab
- pandas
- scikit-learn
- ucimlrepo

##  Data Sources
- UCI Mushroom Dataset
- UCI Dry Bean Dataset
