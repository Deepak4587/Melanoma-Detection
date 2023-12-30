# Melanoma Detection
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. The aim of this project is to build a CNN based model which can accurately detect melanoma.


## Table of Contents
* [General Info](#general-information)
* [Initial Model Creation](#initial-model-creation)
* [Updated Model](#updated-model)
* [Conclusions](#conclusions)


## General Information
- We have received a dataset containing 2357 images of malignant and benign oncological diseases. 
- We are required to build a multiclass classification model using a custom convolutional neural network in TensorFlow which helps in detecting melanoma.
- The given dataset consists of 9 types of disesas among which includes melanoma.
- This solution will be helpful for dermatologists to detect the presence of melanoma in the earky stages.

## Initial Model Creation
- Initial data was created and loaded using keras.
- The model was compiled, trained and visualized.
- It was found that the training and validation accuracies had a significant difference among them.
- This suggests overfittng and we need to find a resolution for that.

## Updated Model
- We have used data augmentation and trained the data again.
- The distribution of data was checked and found out to have class imbalance.
- In order to reduce the class imbalance, we use augmentor. Additional sample classes were added to rectify the problem.
- The data was compiled and trained again after that.
- The accuracy levels got comparable now and we have built a good model.

## Conclusions
- The difference in training and validation accuracies indicate a sign of overfitting. This needs to be corrected.
- Data augmentation is one of the best methods to resolve this.
- We should always look out for classs imbalance as that could affect the model performance.
- The final model should have good linear increase in training accuracy and comparable difference between training and validation accuracies.


## Contact
Created by [@Deepak4587] - feel free to contact me!