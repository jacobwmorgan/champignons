# Classification of Mushrooms using Machine Learning

This project is my undergrad diseration project. 
The goal of this is to compare different models and find the best model for classifying mushrooms.


## Installing dataset

Eventually I will have code to install the dataset automatically

Install the temp dataset from [here](https://www.kaggle.com/datasets/maysee/mushrooms-classification-common-genuss-images)

and add the indiviual folders to the dataset directory

The directory should look like this
```
dataset
├── Agaricus
├── Amanita
├── Boletus
├── Cantharellus
├── Cortinarius
├── Entoloma
├── Hygrocybe
├── Lactarius
├── Russula
├── Suillus

```
:exclamation: An issue ive noticed with this specific dataset is that it will make the dataset twice. If you see a folder with the name "Mushrooms" inside of the dataset, delete it. The directory should look like it does above.

Running ```com_dataset.ipynb``` will create two new pickle files. One for the images and one for the classification labels.

## Model

The model is stored in ```com_ml.ipynb``` and can be edited in there too. If running in vs code you can access the tensorboard via command at the top of the notebook.