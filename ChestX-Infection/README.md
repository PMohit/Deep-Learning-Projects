# Chest Infection Prediction - 
![Python 3.7](https://img.shields.io/badge/Python-3.7-brightgreen.svg) ![scikit-learnn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg)  ![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue.svg)

#  Project Overview
• Created a model that predicts the chest infection.<br/>


# Resources Used
• Packages: pandas, numpy, sklearn, tensorflow, matplotlib,glob,keras, seaborn.<br/>
• Dataset by Kaggle :  https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

 
#  Exploratory Data Analysis (EDA)

# Feature Engineering
• Rescale:  Rescale is a value by which we will multiply the data before any other processing. Our original images consist in coefficients in the 0-255, but such values would be too high for our models to process (given a typical learning rate), so we target values between 0 and 1 instead by scaling with a 1/255. factor.
•shear_range : shear_range is for randomly applying shearing transformations.
•zoom_range:zoom_range is for randomly zooming inside pictures.
•horizontal_flip: horizontal_flip is for randomly flipping half of the images horizontally. 
•These generators can then be used with the Keras model methods that accept data generators as inputs, fit_generator, evaluate_generator and predict_generator.
• Split the data into train and tests sets with a test size of 20%

# Model Building
Algorithms used for this project are as follows:<br/>
• VGG 16-Convolutional Neural Network (CNN)<br/>

![CNN](https://media.geeksforgeeks.org/wp-content/uploads/20200219152207/new41.jpg)

•Classified into 2 categories:<br/>
   * Normal <br/>
   * Pneumonia<br/>



**Please do comment in the repository, if any bugs found .<br/>
 