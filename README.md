# Deep-learning-challenge

# Overview:

The purpose of this analysis is to create a tool to help the nonprofit foundation Alphabet Soup select the applicants for funding with the best chance of success in their ventures.To implement this, I created and trained an artificial neural network (NN) on prior data to see if I can achive over 75% accuracy. 

# Results:

What variable(s) are the target(s) for your model?  IS_SUCCESSFUL
What variable(s) are the features for your model?  APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
What variable(s) should be removed from the input data because they are neither targets nor features? EIN and NAME


The initial model showed a less than 75% accuracy but once retested, I added an additional third layer with 80, 60. 30 neurons respectively and Relu functions. However, this did not increase the accuracy and stayed at 73% which isn't negative but not quite the 75%. For the third attempt, I changed the input_dim from 116 to the number_input_features but it decreased the accuracy to 72%. Overall I'm happy my inital model was close to the 75%. I believe that a supervised learning model can be used to achieve a higher accuratacy like scikitlearn such as random forest or logistic regression methods. 