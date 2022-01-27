# Flight-Fare-Prediction-Using-Flask
This is a end to end data science project where the flight fare has been predicted using Random Forest model.

#Model Training


1.The dataset was collected from kaggle (https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh/) 

2.This dataset contains 10 features and total 10,684 row

3.Before training the model the dataset was pre processed

4.There were both categorical and time date which was converted to numeric value

5.Both Test and Train data were pre processed

6.After Preprocessing the training data data was used for model training. 30% data was used for testing purpose

7.We used Random Forest model for training the data and the R2 score 80.37%

8.After Hyper parameter tuning the R2 score was improves to 81.52%

7.The model was saved in a pickle file for the web app

8. The pickle file can be found in this location(https://drive.google.com/file/d/16vgalYKox9xh_xz760VDMQX4INkEVRTu/view?usp=sharing)



#Web app



1.The Web application was created using Flask and the template was designed using html

2.All the data was inputed through the webapp

3.All these data were analysed using the machine learning model

4.Finally the predicted value was shown by the webapp
