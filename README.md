
**Overview Report Analysis**

  * Data Preprocessing
    
1. What variable(s) are considered the target(s) for your model?
The target of the model is the “Is-successful” column. Means money was used effectively.  
2. What variable(s) are the features for your model?
NAME, TYPE, APPLICATION, CLASSIFICATION, AFFILIATION, ORGANIZATION, CASE_USE, INCOME_AMT, STATUS, ASK_AMT, SPECIAL_CONSIDERATIONS

 3. What variable(s) are neither targets nor features, and should be removed from the input data? (Employer identification) EIN was dropped. The numbers could confuse the system into thinking is important. SPECIAL_CONSIDERATIONS should be dropped because of the small percentage it had. The other drop should be STATUS they are all the same. 
  


* Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why? 
In this model there are three hidden layers each with many neurons. The first activation function was 'relu' but the 2nd and 3rd were 'sigmoid'and the output function was 'sigmoid'. Changing the 2nd and 3rd activation functions to 'sigmoid' also helped boost the accuracy.

2. Were you able to achieve the target model performance?
Yes

3.What steps did you take to try and increase model performance? Converting the NAME column into data points, which has the biggest impact on improving efficiency. And it also required adding a third layer and using the "sigmoid" activation function for the 2nd and 3rd layer.


**Summary**: Summarize the overall results of the deep learning model. 
A good model to recommend is the Random Forest. Using this model for accuracy. 

Overall, the accuracy above 75% were successful by the following 

Name : more than 5 times
Application : T3, T4, T5, T6, T7, T8, T10, T19
Classification : C1000, C2000, C3000, C1200, and C2100 



