# Melenoma Detection using CNN
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Provide general information about your project here.
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- To detect cancer in the earlier stages.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.





## Conclusions
- With basic CNN model , it was found that the model was overfitting due to highly imbalanced data.
- Augementor was used to remove the imbalance of the data by adding 500 images to each classes.
- The final model after augmentation removed the overfitting and gave around 89% accuracy



## Technologies Used
- Tensorflow
- Keras
- Seaborn


## Contact
Created by [@Saibek] - feel free to contact me!


<