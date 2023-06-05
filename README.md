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

## Result
* loss: 0.3875
* accuracy: 0.8550
* val_loss: 0.2092
* val_accuracy: 0.9250
* Model Accuracy Graph
![image](https://github.com/baramizzo58/DTSFGA2022-MLD-Dicoding-Development-FinalProject/assets/119744134/0d198705-1a8d-455e-95ad-273218a7676f)
* Model Loss Graph
![image](https://github.com/baramizzo58/DTSFGA2022-MLD-Dicoding-Development-FinalProject/assets/119744134/e0561d09-186e-4ab6-a2f4-358046ba65d0)

## Saving Model
Save models into TF-Lite format.
