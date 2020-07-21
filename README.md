# Skin Cancer Detection

by Joydip Basu Biswas - joydipj528@gmail.com

Skin cancer is the most common human malignancy, is primarily diagnosed visually, beginning with an initial clinical screening and followed potentially by dermoscopy analysis, a biopsy and histopathological examination
The purpose of this project is to create a tool that considering the image of a mole, can calculate the probability that a mole can be Malignant or Benign.

The dataset is taken from Kaggle. It consists of 1800 pictures of benign moles and 1497 pictures of malignant classified moles. The pictures have all been resized to low resolution (224x224x3) RGB. The task of this kernel is to create a model, which can classify a mole visually into benign and malignant.
Development process and Data
The idea of this project is to construct a CNN model that can predict the probability that a specific mole can be Malignant or Benign.

Data :  

kaggle-https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign

As the dataset is pretty balanced, the model will be tested on the accuracy score, thus (TP + TN)/(ALL).
It has 2 different classes of skin cancer which are listed below :

•	Benign

•	Malignant

Sample images of Benign moles:

![5](https://user-images.githubusercontent.com/65830687/88107255-682c8c80-cbc4-11ea-9a22-d162a6a420d8.jpg)     ![535](https://user-images.githubusercontent.com/65830687/88107443-b5a8f980-cbc4-11ea-8aa4-ab21050ae47b.jpg)   ![450](https://user-images.githubusercontent.com/65830687/88107922-96f73280-cbc5-11ea-895d-efbd9048fa02.jpg)    ![1260](https://user-images.githubusercontent.com/65830687/88107991-b726f180-cbc5-11ea-90e0-be7cab16a2d3.jpg)
 


    








Sample image of Malignant moles:

![3](https://user-images.githubusercontent.com/65830687/88107559-e9841f00-cbc4-11ea-8639-a6822668527b.jpg)     ![762](https://user-images.githubusercontent.com/65830687/88107658-1df7db00-cbc5-11ea-8ffc-6f71090619b4.jpg)    ![381](https://user-images.githubusercontent.com/65830687/88107760-4c75b600-cbc5-11ea-9e04-f619ad8a08cc.jpg)   ![1427](https://user-images.githubusercontent.com/65830687/88107820-6e6f3880-cbc5-11ea-80e5-6b742b4117d7.jpg)





     

In this project I will try to predict 2 different classes of moles using Convolution Neural Network with keras tensorflow in backend and then analyse the result to see how the model can be useful in real lifel scenario.

In this kernel I have followed following 14 steps for model building and evaluation which are as follows:

   •	Importing Essential Libraries

   •	Data Augmentation

   •	Import Data and split into training and test set

   •	Model Building

   •	Fitting into the mode

   •	Summarize history for accuracy

   •	Summarize history for loss

   •	 Prediction



Tools to use: 

•	Tensorflow

•	Keras

•	Python

•	Matplotlib

•	Scikit-learn

•	Jupyter Notebook
                                                                                     


 


.
