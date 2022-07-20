# Melanoma Detection Assignment
Build a CNN based model which can accurately detect melanoma. 

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Links to important documents](https://github.com/suniljadhav/HousePricePrediction/blob/main/README.md#links-to-important-documents)
* [Acknowledgements](#acknowledgements)
* [Contact](https://github.com/suniljadhav/HousePricePrediction/edit/main/README.md#contact)

## General Information
Problem Statement:

Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Goal:

Build a CNN based model which can accurately detect melanoma. 
Build 3 models:
1. Use the provided train images to train the CNN model
2. Expand the train images using data augmentation and then train the CNN model
3. Use Augmentor method to handle the imbalance of class data and then train the CNN model

The following steps are taken as the solution:

1. Import libraries
2. Import image data

[A] Model building & training on the Original Data

3. Load input images into train and validation datasets
4. Visualize the data
5. Create the model
6. Compile the model
7. Train the model # 20 epochs
8. Visualize the results
9. Findings

[B] Model building & training on the Rectified Class Imbalance Data

10. Rectify class imbalances present in the training dataset
11. Create the model after rescaling images 
12. Compile the model
13. Train the model # 30 epochs
14. Visualize the results
15. Findings after Rectified Class Imbalance Treatment

[C] Model building & training on the Rectified Class Imbalance Data using Augmentor

16. Rectify class imbalances present in the training dataset with Augmentor library
17. Load new set of images into train and validation datasets
18. Create the model after rescaling images 
19. Compile the model
20. Train the model # 30 epochs
21. Visualize the results
22. Findings after Rectified Class Imbalance Treatment

- What is the input data that is being used?
  "Skin cancer ISIC The International Skin Imaging Collaboration/Train" - 2239 images from 9 classes
  "Skin cancer ISIC The International Skin Imaging Collaboration/Test" - 118 images 

## Conclusions
- Conclusion 1: Using plain vanilla CNN model, the model overfitted
- Conclusion 2: Using Data Augmentation, the model underfitted
- Conclusion 3: Using Augmentor library to handle class imbalance, the model gave good results.

## Technologies Used
- python 3.x
- numpy
- pandas
- matplotlib
- tensor flow
- keras
- PIL
- cv2

## Links to important documents
- The Python notebook containing 'Melanoma Detection Assignment - By Sunil Jadhav' can be found here (https://github.com/suniljadhav/HousePricePrediction/blob/13246d9b7e1e05590193125c798fcd8ae1329759/Advanced%20Regression%20Assignment%20-%20House%20Price%20Prediction%20(Part%20I)%20%20-%20Model.ipynb).


## Acknowledgements
- This assignment is part of the ML/AI masters programme.


## Contact
Created by [@suniljadhav] - feel free to contact me!
