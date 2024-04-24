# SC1015: Data Science Mini Project - Thinking of Getting A Dog?

School of Computer Science and Engineering \
Nanyang Technological University \
Lab: FCCA \
Group : 5

---

### Description:
This repository contains all the Jupyter Notebooks, datasets, video presentations, and the source materials/references we have used and created as part of the Mini Project for SC1015: Introduction to Data Science and AI. 

This README briefly highlights what we have accomplished in this project. If you want a more detailed explanation of things, please refer to the the Jupyter Notebooks in this repository. They contain more in-depth descriptions and smaller details which are not mentioned here in the README.

## Problem Definition 
**Our Dataset:** [Kaggle](https://www.kaggle.com/datasets/mexwell/dog-breeds-dogtime-dataset) \
**Our Question:** Are we able to predict if a dogbreed is good for novice owners given the various attributes

## Models Used 
1. Multilayer Perceptron(MLP)
2. Random Forest Classifier
3. Decision Tree Classifier
4. Gaussian Naive Bayes

## Conclusion 
- All the models that we used to predict the classes have a relatively low accuracy
- Despite Multilayer Perceptron Model being more complex did not result in a more accurate classification
- Simplier Models such as Random Forest and Decision Tree were able to produce better classification results because it has simpler decision boundaries and is more robust to noise as compared to MLP
- Gaussian Naive Bayes Model has the lowest accuracy in terms of classification

## What could be done on hindsight
- We can modify our problem to a binary classification problem, since our dataset is small(349 sample), reducing the number of classification from 5 to 2 would drastically increase our models' accuracy

## What did we learn from this project?
- Neural Network through implementing the Multilayer Perceptron
- Random Forest Model and Gaussian Naive Bayes Model from sklearn
- Visualising random forest tree using 'graphviz' and 'pydotplus' modules
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score


## References 
- <https://www.kaggle.com/datasets/mexwell/dog-breeds-dogtime-dataset>
- <https://medium.com/@polanitzer/a-multi-layer-perceptron-classifier-in-python-predict-digits-from-gray-scale-images-of-hand-drawn-44936176be33>
- <https://www.researchgate.net/figure/Calculation-of-Precision-Recall-and-Accuracy-in-the-confusion-matrix_fig3_336402347>
- <https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd>
- <https://anantha-kattani.medium.com/visualizing-a-decision-tree-using-graphviz-and-pydotplus-24a046faac0b>
