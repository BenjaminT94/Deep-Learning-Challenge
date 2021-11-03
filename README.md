# Deep-Learning-Challenge
The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
Step 4: Write a Report on the Neural Network Model
For this part of the Challenge, you’ll write a report on the performance of the deep learning model you created for AlphabetSoup.
The report should contain the following:


Overview of the analysis: Explain the purpose of this analysis.<br>
  The purpose of this analysis is to use the features in the provided dataset to create a neural network algorythm that can predict if the applicants of the Alphabet Soup charity will be successful or not. 


Results: Using bulleted lists and images to support your answers, address the following questions.



Data Preprocessing

What variable(s) are considered the target(s) for your model?<br>
  Target variable is "IS_SUCCESSFUL" column<br>
What variable(s) are considered to be the features for your model?<br>
  Features of the model are all columns except "NAME" and "IS_SUCCESSFUL" columns<br>
What variable(s) are neither targets nor features, and should be removed from the input data?<br>
  Columns "EIN" and "NAME" are considered non targets and non features and have been removed appropriately from the input data<br>


Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?<br>
  For the neural network, there are 2 hidden layers with the first having 80 and the second having 30 neurons. I chose for the first and second hidden layers to have the relu activation function and sigmoid for the output layer because I believe these functions are optimal<br>
Were you able to achieve the target model performance?<br>
  My model has 69% accuracy so no, it was not able to achieve the target model performance <br>
What steps did you take to try and increase model performance?<br>
  I had an attempt where I tried to change the activation function of the output layer to tanh and the accuracy got even worse and lowered to a 49%<br>





Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.<br>
  Surprisingly, my initial accuracy score at 69% is better than my score after my attempt to optimize the model. My best theory in the loss of accuracy was because the tanh function ranges from -1 to 1 and therefore, the range is too wide. Just like with any machine learning concepts covered so far, I recommend to use more input data to increase accuracy. Also an alternative method would be to use the Random Forest Classifer due to its ability to use multiple decision trees that also could help in preventing the overfitting of data. 
