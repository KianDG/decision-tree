# Decision Tree Rust Implementation

## Group Members:
- Kian De Guzman (kd29)
- Reese Ramos (reeser3)

## Project Introduction
Description: We will be implementing a decision tree in Rust. This will allow for reading in signal and background data from files, training different decision tree models, saving the models by writing to files, and running the models on other data points.

Goals and Objectives:
- Implement a standard decision tree that continues to split into branches with a miminum number of data points in each final leaf
- Implement random forest, adaptive, and gradient boosting methods
- Implement reduced error, and cost complexity pruning methods

Why This Topic? 
- One of us took a course in high school that described how decision trees work and ways to improve a model by boosting and pruning. We find this idea interesting as classification models are becoming more and more important, so it would be cool to implement decision trees in Rust.

## Technical Overview
Major Components:
- Datapoint class
- Dataset class
- TrainingDataset class
- Classifier trait
- StandardTree class
- StandardClassifier class
- RandomForest class
- RandomForestClassifier class
- AdaboostTree class
- AdaboostClassifier class
- GradientTree class
- GradientClassifier class
- ReducedErrorPrune class
- CostComplexityPrune class




Plan by Checkpoint:
- Checkpoint 1: Implement standard decision tree
- Checkpoint 2: Implement boosting methods
- Final: Implement pruning methods

## Possible Challenges
- Learning Rust traits to create classes that act as equivalents of abstract classes