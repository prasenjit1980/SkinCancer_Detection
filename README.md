# Project Name
> Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

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


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Pandas - version 2.0.3
- NumPy - version 1.24.3
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.2
- Jupyter Notebook 6.5.4
- TensorFlow version: 2.16.1

## Conclusions
1. Accuracy on train and validation set data has increased by using Augmentor library.
2. Overfitting has reduced considerably compared to first case where no augmentation and hyperparameter tuning was used.
   Train Accuracy:  88%
   Validation Accuracy:  69%


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
