# CNN-in-rainfall-runoff-modelling
Code for paper "Deep learning convolutional neural network in rainfall–runoff modelling"
Link: https://iwaponline.com/jh/article/doi/10.2166/hydro.2020.095/73683/Deep-learning-convolutional-neural-network-in
### Author: 
Song Pham Van ; Hoang Minh Le ; Dat Vi Thanh ; Thanh Duc Dang ; Ho Huu Loc ; Duong Tran Anh
### Abstract:
Rainfall–runoff modelling is complicated due to numerous complex interactions and feedback in the water cycle among precipitation and evapotranspiration processes, and also geophysical characteristics. Consequently, the lack of geophysical characteristics such as soil properties leads to difficulties in developing physical and analytical models when traditional statistical methods cannot simulate rainfall–runoff accurately. Machine learning techniques with data-driven methods, which can capture the nonlinear relationship between prediction and predictors, have been rapidly developed in the last decades and have many applications in the field of water resources. This study attempts to develop a novel 1D convolutional neural network (CNN), a deep learning technique, with a ReLU activation function for rainfall–runoff modelling. The modelling paradigm includes applying two convolutional filters in parallel to separate time series, which allows for the fast processing of data and the exploitation of the correlation structure between the multivariate time series. The developed modelling framework is evaluated with measured data at Chau Doc and Can Tho hydro-meteorological stations in the Vietnamese Mekong Delta. The proposed model results are compared with simulations of long short-term memory (LSTM) and traditional models. Both CNN and LSTM have better performance than the traditional models, and the statistical performance of the CNN model is slightly better than the LSTM results. We demonstrate that the convolutional network is suitable for regression-type problems and can effectively learn dependencies in and between the series without the need for a long historical time series, is a time-efficient and easy to implement alternative to recurrent-type networks and tends to outperform linear and recurrent models.

### Create Environment:
Use this command: `conda env create -f environment.yml`

### Commercial Use
This software is provided for research purposes only. A license must be obtained for any commercial application.
