# Upgrad-Melanoma-Detection-Assignment
Melanoma Detection Assignment
>  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

    Actinic keratosis
    Basal cell carcinoma
    Dermatofibroma
    Melanoma
    Nevus
    Pigmented benign keratosis
    Seborrheic keratosis
    Squamous cell carcinoma
    Vascular lesion

Under the exercise we have completed and re-iterated the following:
Model Building & training : 

a. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
b. Choose an appropriate optimiser and loss function for model training
c. Train the model for ~20 epochs
d. Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions


Observations:

    The ultimate model showcases well-balanced performance, displaying no signs of underfitting or overfitting.

    The implementation of class rebalancing has enhanced the model's performance across both training and validation datasets wrt loss function

    Following 37 epochs, the final model attains an accuracy of 84% on the training set and approximately 79% on the validation set.

    The narrow divergence between training and validation accuracies underscores the robust generalization capability of the final CNN model.




<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

    Python - version 3.11.4
    Matplotlib - version 3.7.1
    Numpy - version 1.24.3
    Pandas - version 1.5.3
    Seaborn - version 0.12.2
    Tensorflow - version 2.15.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was based on Upgrad case study


## Contact
Created by [@neelamiimr] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
