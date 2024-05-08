# deep-learning-challenge
# OVERVIEW
 The purpose of this analysis is to create a binary classifier for a non- profit foundation Alphabet Soup, that can predict whether the applicants will be successful if funded.
# RESULTS
# * Data Processing
	 o Target variables are values of column IS_SUCCESSFUL
	 o Feature variables are all other columns except EIN and NAME which  were removed.

# * Compiling, Training, and Evaluating the Model
	 o in the first model, 2 hidden layers with 18,10 neurons were used.In the first optimization model, again same layers but 24 and 11 neurons were used. In the last 	  	   	  model, three layers with 24,11 and  11 neurons were used.
	 o Neither models could not achieve target performance of more than 75%.
	 o Activation functions in the hidden layers are “relu” and in the output layer, its sigmoid function as the output is binary.
<img width="269" alt="model2" src="https://github.com/JollyCJoseph/deep-learning-challenge/assets/151517356/e8633a57-4c21-455b-a65a-b74194219679">


<img width="269" alt="model2" src="https://github.com/JollyCJoseph/deep-learning-challenge/assets/151517356/129a9575-8048-4790-a4c5-4cc24255f2a4">

<img width="267" alt="model3" src="https://github.com/JollyCJoseph/deep-learning-challenge/assets/151517356/d3543fda-dcca-4640-8dd1-cce0c38f81d4">



# SUMMARY
# All three models could not achieve performance of more than 75%.The activation function used in the hidden layer s are ‘relu’.
# Combinations of different activation functions and different combinations of hidden layers and neurons might improve the performance of the model. By creating a method to allow 	 the # kerastuner to decide the activation functions in the hidden layers and number hidden layers and neurons will improve the performance of the model.
