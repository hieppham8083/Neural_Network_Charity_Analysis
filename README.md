# Neural_Network_Charity_Analysis
- The purpose of this analysis was to apply deep-learning neural networks to analyze charitable donations.. Refer to [AlphabetSoupCharity.ipynb](../main/AlphabetSoupCharity.ipynb) and [AlphabetSoupCharity_Optimzation.ipynb](../main/AlphabetSoupCharity_Optimzation.ipynb)

## Challenge
- Perform the following three technical analysis deliverables from [charity_data.csv](../main/charity_data.csv):
- Preprocessing Data for a Neural Network Model (Deliverable 1):
  - Target is the IS_SUCCESSFUL column and the features are every column except IS_SUCCESSFUL column. Refer to image below:
      ![alt text](../main/Deliverable1Xy.png) 
  - Scale the data. Refer to image below:
     ![alt text](../main/Deliverable1Scaler.png) 
-  Compile, Train, and Evaluate the Model (Deliverable 2):
  - There are two hidden layers with 80 and 30 neurons. Also one output layer. Two hidden layers have an activation function "relu" & the output layer is "sigmoid".
      ![alt text](../main/Deliverable2_Complie.png) 
- Was the model able to achieve the target model performance?
  - The target for the model was to be 75% or above, The result was not able to reach the target.
- What steps were taken to try and increase model performance?
  - Changing the number of neurons in the hidden layer, changing the activation function, and changing the number of epochs.
- Optimize the Model  (Deliverable 3):
  - Tried a different activation function (tanh) but no improve.
    ![alt text](../main/Deliverable3_TanhFunction.png)
    ![alt text](../main/Deliverable3_Result.png)
    
 ## Summary
 - The results was only 72.5% and did not reach the target of 75%. Conclusion: the model is not outperforming.
 - In order to increase the accuracy of model, we need to have more data. 
