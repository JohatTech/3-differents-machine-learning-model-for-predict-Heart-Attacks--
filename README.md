# 3-differents-machine-learning-model-for-predict-Heart-Attacks--
Analysis of the performaces of three differents ML model  for predict a heart attack
We use three differents models 
1.K-Nearest Neighbors
2.Random forest Classifier 
3.Neural network 

We choose this threes models because our dataset have a large number of observation compare to the number of features
in both cases we analys the performance of accuracy but also the recall and presicion
because is a prediction of a emergency event we want a high recall performance 

Random Forest classifer performance 
we a max depth of 4.55
![image](https://user-images.githubusercontent.com/86735728/135650748-c8bcd648-0e0b-4b65-991d-9334185afb90.png)

In the presicion a recall performance we get a high performance in the recall for positive in Heart Attack
the kind of value that we are looking for
![image](https://user-images.githubusercontent.com/86735728/135650893-43cb160e-39e1-4d8d-b81b-af9a97b39753.png)


K-Nearest Neighbors performance
after implemnet a program for lookig the best k value and numbers of leaves, we got this values 
![image](https://user-images.githubusercontent.com/86735728/135651471-b435fd32-9e56-4280-9f59-ab7b79621833.png)

And base on those values we train our model and in this image below is the result of the performance in recall that is significantly low compare to the Random Forest model
![image](https://user-images.githubusercontent.com/86735728/135651316-e2db7abf-85f4-4c2b-8475-ec3c46021f4e.png)

Neural Network Model 
In the last model we use a neural network model using a simple classifier algorithm with keras from tensorflow

The evaluation of the performance of the loss function was  significantly goof for this cases
 ![image](https://user-images.githubusercontent.com/86735728/135892425-28cba533-982b-404d-91c3-79fae8db5a47.png)
 
The accuracy of the training data and the validation was similary good with a good sign of no overfitting 
![image](https://user-images.githubusercontent.com/86735728/135892576-efc01bb2-c798-4837-9099-13dfd7b8f2cb.png)

The last evaluation was the recall/presicion and the confusion matrix 
![image](https://user-images.githubusercontent.com/86735728/135892689-afafee91-240f-43c5-afbd-c50f306c9e93.png)
Here we got a high performance in the positive case of heart attack, that is exactly what we want


Conclusion 
The best model who outperformce in the prediction of a positive case of heart attack was random forest classifier and the neural networ,
this models are great for emergency cases in medicine.





