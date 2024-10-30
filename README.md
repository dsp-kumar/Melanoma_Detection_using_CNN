# Melanoma_Detection_using_CNN

This project is focused on building a multiclass classification model using a custom convolutional neural network (CNN) in TensorFlow to accurately detect melanoma from images.

## Table of Contents
- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Contact](#contact)

## General Information
- What is the background of your project?
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the business probem that your project is trying to solve?
A model needs to be built to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Technologies Used
- **TensorFlow - Version 2.14.0**: An open-source platform for machine learning and deep learning.
- **Pandas - Version 2.1.0**: A library for data manipulation and analysis using DataFrames.
- **NumPy - Version 1.25.0**: A library for numerical computing with support for arrays and matrices.
- **Matplotlib - Version 3.8.0**: A plotting library for creating visualizations.
- **Pillow - Version 10.0.0**: An image processing library for opening and manipulating images.

## Conclusions
The model's training and validation accuracy remain constant and low, indicating the model may not be learning effectively. This suggests a need for model tuning or architecture adjustments.
We implemented class rebalancing to reduce overfitting, which lowered the loss but also decreased accuracy significantly. Initially, we worked without ImageDataGenerator, leading to high overfitting. To combat this, we added dropout and used ImageDataGenerator, which helped reduce overfitting. Ultimately, we introduced Batch Normalization and data augmentation, which improved model performance.
High and consistent loss values suggest the model might be underfitting, possibly due to insufficient training epochs or a lack of model complexity.



## Contact
For further information, please contact **DSP Kumar**.



