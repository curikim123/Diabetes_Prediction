# Diabetes Prediction

## How the algorithm works

This is a tool to predict whether you have a chance of having diabetes. The dataset was imported from [here](https://www.kaggle.com/uciml/pima-indians-diabetes-database), which is based off of a previous study conducted among female Pima People as part of the National Institute of Diabetes and Digestive and Kidney Diseases study. 

In order to create a prediction model, a logistic regression was performed based on whether a participant does or does not have diabetes. The results are shown below:

![Logistic regression](https://github.com/curikim123/Diabetes_Prediction/blob/master/images/Logistic%20Regression.png =250x)

Based on this, it was shown that the outcome is associated with four variables- BMI, age, blood pressure, and number of pregnancies- assuming p<0.05. Thus, these four varibles were set as the input variable for the prediction model. Based on this input the algorithm will calculate the percentage that you have diabetes.

## How to use this tool

### Predicting diabetes

![First Page](https://github.com/curikim123/Diabetes_Prediction/blob/master/images/Main%20screen.png | width=100)

Users can input their status on the left panel of the screen as shown below After clicking submit, the chance that you will have diabetes will be shown as percentage on the right. For instance, here it is shown as 35.55%.  

![Example input](https://github.com/curikim123/Diabetes_Prediction/blob/master/images/Prediction.png | width=100)

### Additional information: About the dataset 

![Second tab](https://github.com/curikim123/Diabetes_Prediction/blob/master/images/Second%20tab.png | width=100)

The second tab shows a brief information about this dataset, as well as the link to the original dataset. There are also graphs that indicate the average age, blood pressure, number of pregnancies, and BMI according to diabetes status. 

### Additional information: About the Pima People 

![Third tab](https://github.com/curikim123/Diabetes_Prediction/blob/master/images/Third%20tab.png | width=100)

The third tab shows a brief history about the Pima people, as well as a map showing where they are located. 


