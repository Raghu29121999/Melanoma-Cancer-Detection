# Melanoma Cancer Ditection
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
##### By Visualizing Data there are 9 classes of Cancer M

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

##### Model 1
- Model Training accuracy ~ 0.87 %
- Validation Accuracy is ~ 0.50% 
- Model is over fit
##### Model 2
- model 2 accuarcy decreased compare to model 1

*Seborrheic keratosis has least number of samples 

* Actinic keratosis & Dermatofibroma classes dominate the data in terms proportionate number of samples

##### Model 3

- Model Training accuracy ~ 0.8817
- Validation Accuracy is ~ 0.74

- Model accuracy increase by increasing adding more epochs  
- accuracy increases by tuning hyperparameter


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow
- matplotlib
- numpy 
- pandas
- glob


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




