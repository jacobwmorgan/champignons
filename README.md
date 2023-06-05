# Classification of Mushrooms using Machine Learning

This project is my undergrad diseration project. 
The goal of this is to compare different models and find the best model for classifying mushrooms.


## Installing dataset

Install the temp dataset from [here](https://www.kaggle.com/datasets/maysee/mushrooms-classification-common-genuss-images)

Store it in google drive and mount it to the notebook

Change the variable ```DATADIR``` to the path of the dataset

For example 
```DATADIR = "/content/drive/MyDrive/Mushrooms/dataset"```

The directory should look like this
```
dataset
├── Agaricus
├── Amanita
├── Boletus
├── Cortinarius
├── Entoloma
├── Hygrocybe
├── Lactarius
├── Russula
├── Suillus
```

## Model

I train three models.

1. Champignon-Net (my own model)
2. [EfficientNet-B1](https://www.tensorflow.org/api_docs/python/tf/keras/applications/efficientnet)
3. [ResNet](https://www.tensorflow.org/api_docs/python/tf/keras/applications/resnet)

## Disseration
Read the diss [here](https://github.com/jacobwmorgan/champignons/blob/main/Undergrad_Dissertation-3.pdf)
