# Neural_Network_Charity_Analysis

## Overview of the Analysis
### The objective of this exercise is to demonstrate how to Load, Build, Train, and Test, and optimize a neural network to help identify under what circumstances a loan will be successful.

### The first task was to load and train an initial model using two hidden layers:
- First Layer: 80 Nodes using ReLu
- Second Layer: 30 Nodes using ReLu
- Output Layer: Sigmoid

### The results were:
- Loss: 56%
- Accuracy: 73%

### This is the baseline figures in which the models will be trained to beat.

## Results
### To answer the questions directly from the Module.

### Data Processing
- What variables are considered the targets for you model?
  - IS_SUCCESSFUL
- What variables are considered to be the features for your model?
  - APPLICATION_TYPE, AFFLIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT 
- What variables are neither targets nor features, and should be removed from the input data?
  - EIN, and NAME

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

  - First Optimization:
    - First Layer: 80 Nodes using ReLu
    - Second Layer: 30 Nodes using ReLu
    - Third Layer: 20 Nodes using ReLu
    - Output Layer: Sigmoid
    
  - Second Optimization:
    - First Layer: 100 Nodes using ReLu
    - Second Layer: 50 Nodes using ReLu
    - Third Layer: 25 Nodes using ReLu
    - Output Layer: Sigmoid
            
  - Third Optimization:
    - First Layer: 200 Nodes using tanh
    - Second Layer: 150 Nodes using tanh
    - Third Layer: 100 Nodes using tanh
    - Output Layer: Sigmoid

- Were you able to achieve the target model performance?

  - None of the three above models were able to achieve any standards above 74%.
  - The bare minimum for a passing metric is 75%.  Hence none of the trained models are considered passing.

- What steps did you take to try and increase model performance?
  - Increased Node Numbers
  - Increased Hidden Layers
  - Different Layer Models

## Summary
### Overall there could be multiple different techinques for increasing the accuracy.  More hidden layers, different classification models, and increasing nodes.  Simply spending time may increase the accuracy figures to figure out the best fit.

  

     
