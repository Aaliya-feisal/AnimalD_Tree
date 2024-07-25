# Animal Classification using Decision Trees

## Overview

This project aims to classify animals based on various features using a Decision Tree Classifier. The dataset includes attributes such as hair, feathers, milk production, and more. The primary objective is to build a decision tree model to predict the class of animals and evaluate its performance.

## Dataset

The dataset contains the following columns:

- **Sr**: Serial number
- **Hair**: Presence of hair (1: Yes, 0: No)
- **Feathers**: Presence of feathers (1: Yes, 0: No)
- **Eggs**: Lays eggs (1: Yes, 0: No)
- **Milk**: Produces milk (1: Yes, 0: No)
- **Airborne**: Can fly (1: Yes, 0: No)
- **Aquatic**: Lives in water (1: Yes, 0: No)
- **Predator**: Is a predator (1: Yes, 0: No)
- **Teeth**: Has teeth (1: Yes, 0: No)
- **Backbone**: Has a backbone (1: Yes, 0: No)
- **Breathes**: Breathes air (1: Yes, 0: No)
- **Venemous**: Is venomous (1: Yes, 0: No)
- **Fins**: Has fins (1: Yes, 0: No)
- **Legs**: Number of legs
- **Tails**: Has a tail (1: Yes, 0: No)
- **Domestic**: Is domesticated (1: Yes, 0: No)
- **Catsize**: Size is similar to a cat (1: Yes, 0: No)
- **Class**: Class of the animal (target variable, binary: 1 for specific class, 0 otherwise)

## Project Steps

### Data Preparation
- Load the dataset.
- Replace class values `2, 3, 4, 5, 6, 7` with `0` to make the classification binary.

### Model Training
- Split the data into training and testing sets.
- Train a Decision Tree Classifier on the training set.

### Model Evaluation
- Predict the classes for the test set.
- Calculate the accuracy of the model.
- Identify important features and decision paths leading to class 1.

### Visualization
- Generate and save a decision tree visualization.

## Results

- The decision tree model achieved an accuracy of 100% on the test set.
- The most important feature leading to class 1 was `Milk`.

## Conclusion

This project demonstrates how to use a decision tree classifier to predict animal classes based on various features. The model achieved perfect accuracy on the test set, suggesting that the presence of milk is a significant factor in classifying the animals in this dataset. Further steps could include testing for overfitting and applying cross-validation to ensure the model's robustness.


