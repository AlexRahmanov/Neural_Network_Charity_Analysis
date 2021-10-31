# Neural_Network_Charity_Analysis

# Purpose
The purpose of this analysis was to predict which charity efforts for AlphabetSoup to back, based on a determination of the success of the effort using Deep Learning Neural Network models.

# Summary
These results noted an accuracy of 72% which is nearing but not achieving the target of 75% which was sought. Random forest classifiers may also have been appropriate to solve this problem, as they take an ensemble of decision trees to make final classification decisions.

# Results
Data Preprocessing
1.Target variable: IS_SUCCESSFUL
2.Features of the model: APPLICATION_TYPE (bucketed into T3, T4, T5, T6, T19, and Other), AFFILIATION, CLASSIFICATION (bucketed into C1000, C1200, C2000, C2100, C3000, and Other), USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
3.Variables removed: EIN and NAME
4.Additional variables removed during optimization attempts: STATUS and SPECIAL_CONSIDERATIONS

# Compiling, Training, and Evaluating the Model
1.Layers and activation functions in AlphabetSoupCharity: two hidden layers (the first with Rectified Linear Unit (ReLU), the second with Sigmoid), output layer (with Sigmoid)
2.Layers and activation functions in optimization code: three hidden layers and output layer (all with Sigmoid)
3.I was unable to achieve target model performance
4.Steps taken to increase target model performance: Dropped two variables (STATUS and SPECIAL_CONSIDERATIONS) entirely, added a third hidden layer, changed activation function of the second hidden layer to Sigmoid.

