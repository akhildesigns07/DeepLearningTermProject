Absolute Humidity Prediction Using ANN and RNN
This project aims to predict Absolute Humidity (AH) using Artificial Neural Networks (ANN) and Recurrent Neural Networks (RNN). We utilize environmental data such as CO (Carbon Monoxide), NOx, C6H6 (Benzene), and Temperature to train the models and predict AH values.

Objective
The goal of this project is to develop deep learning models that predict Absolute Humidity (AH) based on various environmental sensor readings. We aim to explore and implement Artificial Neural Networks (ANN) and Recurrent Neural Networks (RNN), for more accurate predictions.

Data Description
The dataset used in this project consists of environmental sensor data, including:

CO (GT): Carbon Monoxide concentration
NOx (GT): Nitrogen Oxide concentration
C6H6 (GT): Benzene concentration
T: Temperature
RH: Relative Humidity
AH: Absolute Humidity (target variable)
The data also includes sensor readings such as PT08 for various gas detectors, which are used for predicting AH.

Models Used
Artificial Neural Networks (ANN): A basic feedforward neural network was used to capture non-linear relationships between the features and the target variable.

Recurrent Neural Networks (RNN): RNNs are employed to capture any sequential dependencies in the data (though the dataset may not strongly require it).
