# What's Cooking
This repository contains the code for our final project for Data Mining course (NDBI023) at the Charles University, Faculty of Mathematics and Physics.

## Goal
The goal is to understand which ingredients are likely to be grouped together by performing Market Basket Analysis and to predict the category of a dish's cuisine given a list of its ingredients. 

## Dataset
We've used the free dataset from the Kaggle's [What's Cooking](https://www.kaggle.com/c/whats-cooking) competition, that contains  3 features: cuisine, recipe id, ingredients


An example of a recipe node in `data/train.json`:

```
 {
 "id": 24717,
 "cuisine": "indian",
 "ingredients": [
     "tumeric",
     "vegetable stock",
     "tomatoes",
     "garam masala",
     "naan",
     "red lentils",
     "red chili peppers",
     "onions",
     "spinach",
     "sweet potatoes"
 ]
 }
```

## Tasks
### Exploratory Analysis
### Preprocessing
Extracting and encoding the features
### Market Basket Analysis
We performed MBA to understand which ingredients are frequently grouped together in defferent cuisines.
### Predictive Analysis
We performed a comparison of different predictive models:
- Logistic Regression
- Gaussian Bayes classifier
- Random Forest classifier
- KNN classifier
- Neural Network

## Notebooks
The code we used for analysis is located in Jupyter notebooks `whats-cooking.pdf` and `whats-cooking-mba.pdf`.

## Slides
A summary or our results can be found in `slides.pptx` and `slides.pdf`.


