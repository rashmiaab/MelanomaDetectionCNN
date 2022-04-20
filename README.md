# MelanomaDetectionCNN
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. In this Project we need to provide a solution which can evaluate images and alert the dermatologists about the presence of melanoma. Thereby this project has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Motivation: To create a multiclass classification model using a custom convolutional neural network in tensorflow

Data Summary:

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of some moles images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Seborrheic keratosis
Squamous cell carcinoma
Pigmented benign keratosis
Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- This Project comprises of total three models built.
- Model M1 when built we see huge difference between Training and Validation Accuracy which was due to data overfitting.
- Model M2 we overcome the overfitting problem using data augmentation and drop out methods. Yet there is a drop in overall accuracy in model M2 than in model M1.
- Model M3 we overcome drop in accuracy in model M2 by using data augmentation to address class imbalance problem and finally we see improvement in accuracy and less accuracy and loss difference between training and validation data sets .

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - v0.25.1
- Numpy - v1.16.5
- Matplotlib - v3.3.2
- Seaborn - v0.9.0
- Sklearn - v0.21.3
- Statsmodel - v0.10.1
- Google Collab

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upgrad CNN Assignment
- This project was based on https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53.


## Contact
Created by [@rashmiaab] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
