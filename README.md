# Automobile-Car-Price-Prediction-using-AzureML-Studio
 Using Azure Machine Learning studio, To create a Linear Regressor model to predict the price of an automobile with its features (like horsepower,peakrpm,engine-type,body-style etc...).

Problem Statement:
The project is to predict the Automobile Price based on the features of an automobile (horsepower,peakrpm,engine-type,body-style etc...).

Using Azure Machine Learning studio, To create a Linear Regressor model to predict the price of an automobile with its features (like horsepower,peakrpm,engine-type,body-style etc...).

The main objective behind the project is to predict the price of an automobile with its features (like horsepower,peakrpm,engine-type,body-style etc...)..For this implementation first we need to get the data in .csv format. We can use the sample data set [Automobile price data _Raw_.csv] provided in the platform itself. The raw data is completely spread in our blank canvas. The attributes includes make, body-style, wheel-base, engine-size, horsepower, peak-rpm and highway-mpg. Preprocessing of data is done before training and analyzing the model. The data must be clean so that the model can predict correctly. For this purpose the empty[Null] values are removed by using column dataset model. Then split the data and then pass the results to the Two Class Boosted decisions algorithm module to train the model. Finally evaluate them. Now the data is ready, constructing a predictive model consists of training and testing. We'll use our own or sample data to train the model, and then we'll test the model to see how accurately it is able to predict price of the automobile.

Project Link : https://gallery.azure.ai/Experiment/Car-Price-Estimator-Predictive-Exp-using-linear-regression-by-harsha

Tool used : Azure Machine Learning Studio (Classic).

Azume ML Studio:
Azure Machine Learning studio is a web portal in Azure Machine Learning that contains low-code and no-code options for project authoring and asset management. It's a GUI-based integrated development environment for constructing and operationalizing Machine Learning workflow on Azure.

Steps

Demo Images :

->Data Preprocessing

![image](https://user-images.githubusercontent.com/74779796/183276510-4fba39a9-cef3-470d-8531-d994b43df465.png)
 
 note:
 The normalized losses has 41 missing values to handel that the missing value rows are dropped from the dataset.
 
 ![image](https://user-images.githubusercontent.com/74779796/183276567-be4e4e41-42ca-41e0-b6f1-07cb83131061.png)

->Feature Selection 
![image](https://user-images.githubusercontent.com/74779796/183276583-02e8ab5b-4ba3-4045-b4ad-a5bc0c759886.png)

Note:
The mentioned features are selected from the dataset as the price field depends more on these fields.

-> Training Testing Split
![image](https://user-images.githubusercontent.com/74779796/183276630-476507c8-b6ab-4f7b-a40a-2f86d2b21fd8.png)

Note:
The dataset is splitted into training and testing data using split data. 70% of data for training and 30% of data for testing.

->Model Training Image:

![image](https://user-images.githubusercontent.com/74779796/183276683-205391bd-603f-4178-bf89-165996df667f.png)

Note:
The model is trained to predict the price column using linear regression algorithm 
Linear Regression Algorithm :
Linear regression performs the task to predict a dependent variable value (y) based on a given independent variable (x). So, this regression technique finds out a linear relationship between x (input) and y(output). Hence, the name is Linear Regression.
In the figure above, X (input) is the work experience and Y (output) is the salary of a person. The regression line is the best fit line for our model.
Formula :
Y_i=f(X_i, \beta)+e_i

![image](https://user-images.githubusercontent.com/74779796/183276315-3addcd1c-4ef0-4e09-beb4-66f5a3150ad8.png)


->Model Estimation:

![image](https://user-images.githubusercontent.com/74779796/183276416-555a3485-0e0a-4ac1-b788-b388772f673a.png)
![image](https://user-images.githubusercontent.com/74779796/183276438-f1bdd9fb-659d-4eae-90bc-0a04820e77c3.png)


->Input Data For Prediction:

![image](https://user-images.githubusercontent.com/74779796/182375380-bd37c409-c568-4894-8ce0-225d4ed1afea.png)

![image](https://user-images.githubusercontent.com/74779796/182375465-43e4991b-7849-4784-9579-31dd0b1883be.png)



->predicted Price:

![image](https://user-images.githubusercontent.com/74779796/182374938-f4a8bfb2-c142-4c5b-9201-27e65fc4f10b.png)


Demo video:



https://user-images.githubusercontent.com/74779796/182600317-3f2f1f8a-56e1-4a71-a0cb-b63327399b5e.mp4


