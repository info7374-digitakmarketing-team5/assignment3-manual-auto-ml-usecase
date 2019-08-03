# Manual and Azure ML Studio

#### Web Application Link for User click prediction ad use case : https://userclickpredictor.herokuapp.com/

#### User Doc for Application:

The web application will consume user input for users demographic data and display comparison between manual and Azure model.

#### Clat Document : https://codelabs-preview.appspot.com/?file_id=1Vn_UxG0kBE-Ia6PLEZqKmBLq5LOBqvEYquG_iMidWyE#0

#### Use Cases :
 1. User click prediction ad
 2. Churn prediction
 3. Predicting next purchase date (With Auto ML)
 4. CLTV Prediction
 5. Market Response Prediction

#### Dataset 

Datasets for each use case in inside its perticular folder:

• https://github.com/info7374-digitakmarketing-team5/assignment3-manual-auto-ml-usecase/blob/master/churn%20prediction/Data/Godaddy_ChurnData.csv

• https://github.com/info7374-digitakmarketing-team5/assignment3-manual-auto-ml-usecase/blob/master/user%20click%20prediction%20ad/data/advertising.csv

• https://github.com/info7374-digitakmarketing-team5/assignment3-manual-auto-ml-usecase/blob/master/predicting%20next%20purchase%20date/data/transactions.csv

• https://github.com/info7374-digitakmarketing-team5/assignment3-manual-auto-ml-usecase/blob/master/market%20response/data/Test.csv


This repository contains end-to-end tutorial-like code samples to help solve
the use cases using machine learning and Azure ML studio.

#### Python Notebooks

We have one module for each case for manual implementation of predictive models for use cases.

1.  *click prediction demographic flask* - Flask Application Models for User click prediction ad use case

    +   Flask Python files to call pickle file (texts and labels).
    +   html in the static folder
     
2.  *Targeting the right audience to predict Ad clicks.ipynb* - Manual python for predicting Ad clicks.

3.  *Churn Prediction3.ipynb* - Manual python for predicting Churn of customers.

4.  *Predicting Customer Next Purchase Day and AutoML.ipynb* - Manual python for predicting Churn of customers Next Purchase Day
    +   Also implemented the same in AutoML
    
5.  *Market Response Prediction* - Manual python for predicting Market response for customers

6.  *Customer Lifetime Value Prediction.ipynb* - Manual python for predicting Customer Lifetime Value

#### The repository also has Azure ML studio web service end point for each of the use cases
    




