# DTSFGA2022-MLD-Dicoding-Development-FinalProject
Final Project of Machine Learning Developer (Learn Machine Learning Development Stage) Training in Fresh Graduate Academy Program (Digital Talent Scholarship 2022).

## Project Explanation
Creating Image Classification Model Deployment.

## Dataset
`Using shoe-vs-sandal-vs-boot-dataset-15k-images.zip` dataset from https://www.kaggle.com/datasets/hasibalmuzdadid/shoe-vs-sandal-vs-boot-dataset-15k-images

## Data Pre-Processing
* Using ImageDataGenerator
  * Using `validation_split` = 0.2

## Data Modelling
* Using Sequential Model
* Model is compiled with `categorical_crossentropy` loss function, `adam` optimizer, and using `accuracy` metrics
* Using callbacks with 92% val_accuracy
