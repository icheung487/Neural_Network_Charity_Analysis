# Neural_Network_Charity_Analysis
# Overview of the analysis: Explain the purpose of this analysis.
We were hired by Alphabet Soup to help determine which foundation would be the best investment for them.  By building a machine learning model and neural netowrk, we will create a binary classifier to help find a prediction.  The purpose to is review all 34,000 organization to find the best fit for the Alphabet Soup a long-term invesment and partnship. 

# Data Preprocessing
What variable(s) are considered the target(s) for your model?
* The columns EIN and Name were removed from the input data and dropped from the dataframe. 
* The column IS_SUCCESSFUL is considered the target for our deep learning neural network while the other are features.  

# Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
* For my neural network model, I had 2 hidden layers.  My first layer was 8 and second layer 5. 

Were you able to achieve the target model performance?
* My model was close to the goal of 75%.  It was at 73%. 

What steps did you take to try and increase model performance?
* I tried to increase my layers, which caused a decrease in my accuracy. 

#Summary: 
* After optimization, my accuracy score declined so the initial model provided a better results than after the optimization. This was proabably due to overfitting.  
