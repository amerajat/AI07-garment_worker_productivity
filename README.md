# AI07-garment_worker_productivity

## 1. Overview
Ther purpose of this project is to predict the productivity of garment worker. This project use the dataset from 	[
Productivity Prediction of Garment Employees Data Set](https://archive.ics.uci.edu/ml/datasets/Productivity+Prediction+of+Garment+Employees) and was created using Google Colab. The framewok used is Pandas, Scikit-learn and TensorFlow Keras. 

## 2. Aim

The dataset is used as a regression purpose and the aim of this project is to predict the productivity performance of the working teams in the factories. 


## 3. Methodology
### Data preprocessing
The data is in .csv form and was saved in Google Drive before it was loaded to the Google Colab. The data was cleaned by removeing unwanted features, all categorical variable and label was encoded, filling in average value to the Nan value and splitted into train and test set with the ratio of 70 -30

### Model
The regression problem was handled by using the feedfoward neural network. The structure of the model is ![garment worker productivity jpg](https://user-images.githubusercontent.com/92585515/182045330-13889390-f4a2-4fa4-bae0-f11f20a4fc8e.png)


Model is then trained with batch size pf 32 in 100 epochs. Training stops at epoch 300 and obtain loss of 0.026 with mean absolute error of 0.121

![garment worker productivity jpg](https://user-images.githubusercontent.com/92585515/182045489-611e8e02-055c-4580-a510-8e0716ad41be.png)

![plot garment worker productivity jpg](https://user-images.githubusercontent.com/92585515/182045552-8e555d70-b17f-4bd4-8da4-406e604c56a5.png)

## 4.Result

The performance metric to evaluate the model used is  mean absolute error The result are plotted to the predicted vs label. To acgieve the aim of this project the plotted graph should have a porper fit of a straight line

![pred graph garment worker productivity jpg](https://user-images.githubusercontent.com/92585515/182045767-946738f6-d0b8-46ef-a514-17e92927df97.png)


