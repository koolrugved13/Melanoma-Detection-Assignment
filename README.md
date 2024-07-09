# Project Name
> 


## Table of Contents
* [General Info](#general-information)
* [Dataset Info](#dataset-information)
* [Technologies Used](#technologies-used)
* [Project Pipeline](#project-pipeline)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma.
In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. 
The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. 
Melanoma skin cancer is highly curable if it gets identified at the early stages
It accounts for 75% of skin cancer deaths.A solution that can evaluate images and alert dermatologists about 
the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Dataset Information
We have used Skin cancer ISIC The International Skin Imaging Collaboration Data set.
These dataset consists of 2357 images of malignant and benign oncological diseases classes.
All images were sorted according to the classification taken with ISIC, and all subsets were divided
into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

- Actinic keratosis              - 114 images 
- Basal cell carcinoma           - 376 images
- Dermatofibroma                 - 95  images
- Melanoma                       - 438 images
- Nevus                          - 357 images
- Pigmented benign keratosis     - 462 images
- Seborrheic keratosis           - 77  images
- Squamous cell carcinoma        - 181 images
- Vascular lesion                - 139 images
 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy lib.
- pandas lib.
- matplotlib lib.
- seaborn lib.
- Tensorflow lib.
- Keras module from Tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Project Pipeline
- Data Reading/Data Understanding → Defining the path for train and test images
- Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
- Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset
- Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs
- Write your findings after the model fit, see if there is evidence of model overfit or underfit
- Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data :
 - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
 - Choose an appropriate optimiser and loss function for model training
 - Train the model for ~20 epochs
 - Write your findings after the model fit, see if the earlier issue is resolved or not? **Class distribution: **
 - Examine the current class distribution in the training dataset
 - Which class has the least number of samples?
 - Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances:
 - Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:
 - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
 - Choose an appropriate optimiser and loss function for model training
 - Train the model for ~30 epochs
 - Write your findings after the model fit, see if the issues are resolved or not?
 - The model training may take time to train and hence you can use Google colab.


## Contact
Created by [@koolrugved13](#@koolrugved13) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
