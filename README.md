# ChicagoCrimePrediction

Crime is a menace that every country is facing because of which an attempt is being made to incorporate **Artificial Intelligence** in reducing crime. Our aim is to build a model which would work on crime data. The data which has been taken reflects reported incidents of crime that occurred in the City of **Chicago** from **2012** to **2017**. From this data, the aim of the model is to explore crime data in **Chicago** and showcase the implementation of a predictive model to find which particular region or part of the city is more affected with crime i.e., finding the regions with **higher threat levels** and **danger levels**. This can be done by **predicting the type of crime that might most likely occur given the location and time**.


# Installation commands

No specific software is required. Code can be executed in **google colaboratory**.

##  **Software/Hardware Requirement**

**Google colaboratory** OR any other **notebook** which supports **Python3**.

## **Instructions to run model**

Two Methods

 1. First Method
	 Download kaggle.json file (already uploaded on Git)
	 Open File 'New_attempt.ipynb' and Start Running Cells
	 Downloaded kaggle.json file needs to be uploaded in Colab
	
 2. Second Method
 	  
	  Google colab program link "https://colab.research.google.com/gist/sujithsagar217/f7e698a81dfeb694276786f053155e2a/new_attempt.ipynb" .
	  
	  Download Data Set From “https://drive.google.com/file/d/1M1-aNTSlAoubyN-kg6KKJgKstiTP8RpH/view?usp=sharing .”

## **Algorithms used**

 1. KNN
 2. Random Forest
 3. XG Boost
 4. Bagging Classifier
 5. Logistic Regression

## Result
|Algorithm Used|Accuracy in % |
|--|--|
|  KNN|85.47  |
|Random Forest|99.99|
|XG Boost|91.18|
|Bagging|92.51|
|Logistic Regression|32.09(until reaching limit)|


As it is evident from the table, Random Forest Classifier works best for the model while KNN works least among them. Logistic Regression not being a tree based classifier encounters a technical limit.


