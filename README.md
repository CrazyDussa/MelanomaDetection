# Melanoma Detection
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. We need to build a CNN based model which can accurately detect melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- We need to build a CNN based model which can accurately detect melanoma.
- The data set contains the following diseases: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We built CNN model on 2357 images of malignant in which our model was overfit.
- We created Image augmention layer(Flip, Rotation and Zoom) and built CNN model which didn't learn much from data due to lesser number of samples.
- We created model by adding 500 Images to each class which are created through Image Augmentation. This model is also overfit.
- We can improve the perfomance of CNN model by Hyperparameter Tuning further.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.15.0
- keras - version 3.0.5
- matplotlib - version 3.7.5
- seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was based on the International Skin Imaging Collaboration (ISIC) provided information.


## Contact
Created by Venkata Saikrishna Dussa[@CrazyDussa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
