# Melanoma Detection

> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- Provide general information about your project here.
  - build a CNN based model which can accurately detect melanoma
- What is the business probem that your project is trying to solve?
  - A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
  - The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

> Project Pipeline

<b>Data Reading/Data Understanding →</b> Defining the path for train and test images <br>
<b>Dataset Creation→</b> Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180\*180.<br>
<b>Dataset visualisation →</b> Create a code to visualize one instance of all the nine classes present in the dataset <br>
<b>Model Building & training :</b> <br>

- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~20 epochs
- Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit.<br>

<b>Chose an appropriate data augmentation strategy to resolve underfitting/overfitting</b><br>
<b>Model Building & training on the augmented data :</b><br>

- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).<br>
- Choose an appropriate optimiser and loss function for model training<br>
- Train the model for ~20 epochs<br>
- Write your findings after the model fit, see if the earlier issue is resolved or not?<br>

<b>Class distribution:</b> Examine the current class distribution in the training dataset <br>

- Which class has the least number of samples?<br>
- Which classes dominate the data in terms of the proportionate number of samples?<br>

<b>Handling class imbalances:</b> Rectify class imbalances present in the training dataset with Augmentor library.<br>
<b>Model Building & training on the rectified class imbalance data :</b>

- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).<br>
- Choose an appropriate optimiser and loss function for model training<br>
- Train the model for ~30 epochs<br>
- Write your findings after the model fit, see if the issues are resolved or not?<br>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Conclusion 1 from the analysis
  - The model is an overfit.
- Conclusion 2 from the analysis
  - After image augmentatioin, the model accuracy has increased.
- Conclusion 3 from the analysis
  - After using image augmentor, the model accuracy is further increased, but now the model is underfit.
- The model performance can be improved by adding more layers and removing dropout layers, and by tuning the hyperparameters.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Python - version 3.9.7
- Pandas - version 1.3.4
- Keras - version 2.9.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@sanngeet] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
