# Neural_Network_Charity_Analysis

## Overview of the analysis
Utilize deep learning neural networks to analyze and classify the success of charitable donations.

## Data Preprocessing

-Variable being targeted is the IS_SUCCESSFUL column

-All columns except dropped columns.

-EIN and NAME are dropped as they are identification columns.

## Compiling, Training, and Evaluating the Model 

-Model was made with an input feature, two hidden layers (80 neurons and 30 neurons) and an output layer. Activation function for hidden layers and sigmoid for output layer.

-Target was 75% or above. Target was not met.

-First change was to add additional neurons to the hidden layers. Second change added a hidden layer. Final change was changing activation functions.

## Summary
-Adding additional neurons to the hidden layers changed the accuracy to 73%

-Adding additional hidden layer changed the accuracy to 72.9%

-Changing the activation function changed the accuracy to 72.8%
