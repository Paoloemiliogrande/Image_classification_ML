# Machine Learning Project - Image Classification

This is the official repository for the *Machine Learning project* handled by Elisa, Joshua and Paoloemilio. The task is "Image Classification" 

## Project Description
The objective is to construct a model capable of accurately classifying images into their
respective categories. Initially, thorough analysis of the dataset is deemed necessary. This
entails examining its structure and meticulously cleansing it. The cleaning phase is pivotal as
well-organized data simplifies subsequent tasks significantly. Key considerations during this
phase include verifying image sizes, brightness levels, eliminating blank spaces, and addressing
similar factors. During the modeling phase, meticulous attention is directed towards selecting
optimal hyperparameters and ensuring model accuracy to mitigate overfitting and other
undesirable outcomes. Additionally, it is advisable to evaluate the model's performance with
new data to validate its robustness.

## Dataset Features
- more than 2000 images of scanned documents in .tif format
- 4 different classes (resumè, advertisement, emails, Handwritten documents)

## Models used
- **Transfer Learning** with *VGG16*
- **Deep Convolutional Neural Network**
- **Region-based CNN**
For the weights of the model please find out the folder "model_weights" which can be found in the folder "models"

## Structure of the repository
- **EDA.ipynb**: self explanatory
- **data** folder: it contains the links to download the document images required to perform this task
- **models** folder: it contains the different notebooks used to train, test and evaluate our models. Moreover there is subfolder called **model_weights** from which you can download the weights of our models


## Additional Information

In case of any problem with the data loading, please reach out our team. Below you can find our emails:

- [Joshua Brauner (group referent)](mailto:joshua.brauner@studenti.luiss.it)
- [Elisa Dobici](mailto:elisa.dobicil@studenti.luiss.it)
- [Paoloemilio Grande](mailto:paoloemilio.grande@studenti.luiss.it)
