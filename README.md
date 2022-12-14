# Deep-Learning-Charity-Funding-Predictor
# Unit 21 Homework: Charity Funding Predictor

## Background

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

* **EIN** and **NAME**—Identification columns
* **APPLICATION_TYPE**—Alphabet Soup application type
* **AFFILIATION**—Affiliated sector of industry
* **CLASSIFICATION**—Government organization classification
* **USE_CASE**—Use case for funding
* **ORGANIZATION**—Organization type
* **STATUS**—Active status
* **INCOME_AMT**—Income classification
* **SPECIAL_CONSIDERATIONS**—Special consideration for application
* **ASK_AMT**—Funding amount requested
* **IS_SUCCESSFUL**—Was the money used effectively


### Step 4: Write a Report on the Neural Network Model

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for AlphabetSoup.

The report should contain the following:

1. **Overview** of the analysis: Explain the purpose of this analysis.

** The purpose Charity-Funding-Predictor analysis is used to determine if applicants would be successfully funded by Alphabet soup, whom previously funded by over 30,000 organizations 

2. **Results**: Using bulleted lists and images to support your answers, address the following questions.

  * Data Preprocessing
    * What variable(s) are the target(s) for your model?
    * What variable(s) are the features for your model?
    * What variable(s) should be removed from the input data because they are neither targets nor features?
  
* Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * Were you able to achieve the target model performance?
    * What steps did you take in your attempts to increase model performance?


![](https://github.com/HanaTafesse/Deep-Learning-Charity-Funding-Predictor/blob/main/Resources/image/2022-08-27%20(6).png)

### Report_df(AlphabetSoupCharity)
model_loss, model_accuracy = nn.evaluate(X_test_scaled,y_test,verbose=2)
print(f"Loss: {model_loss}, Accuracy: {model_accuracy}")

268/268 - 1s - loss: 0.5624 - accuracy: 0.7235 - 733ms/epoch - 3ms/step
Loss: 0.562383770942688, Accuracy: 0.723498523235321

![](https://github.com/HanaTafesse/Deep-Learning-Charity-Funding-Predictor/blob/main/Resources/image/Report_df.png)


### Report_1_df (AlphabetSoupCharity_Optimzation_1)
model_loss, model_accuracy = nn.evaluate(X_test_scaled,y_test,verbose=2)
print(f"Loss: {model_loss}, Accuracy: {model_accuracy}")

268/268 - 0s - loss: 0.6607 - accuracy: 0.6075 - 165ms/epoch - 615us/step
Loss: 0.6607240438461304, Accuracy: 0.607463538646698

![](https://github.com/HanaTafesse/Deep-Learning-Charity-Funding-Predictor/blob/main/Resources/image/Report_1_df.png)


  ### Report_2_df(AlphabetSoupCharity_Optimzation_2)
  model_loss, model_accuracy = nn.evaluate(X_test_scaled,y_test,verbose=2)
print(f"Loss: {model_loss}, Accuracy: {model_accuracy}")

268/268 - 1s - loss: 0.6418 - accuracy: 0.6199 - 524ms/epoch - 2ms/step
Loss: 0.6417614221572876, Accuracy: 0.6199417114257812

![](https://github.com/HanaTafesse/Deep-Learning-Charity-Funding-Predictor/blob/main/Resources/image/Report_2_df.png)


  ### Report_3_df (AlphabetSoupCharity_Optimzation_3)

  model_loss, model_accuracy = nn.evaluate(X_test_scaled,y_test,verbose=2)
print(f"Loss: {model_loss}, Accuracy: {model_accuracy}")

268/268 - 0s - loss: 0.5629 - accuracy: 0.7284 - 181ms/epoch - 674us/step
Loss: 0.5628575086593628, Accuracy: 0.728396475315094

![](https://github.com/HanaTafesse/Deep-Learning-Charity-Funding-Predictor/blob/main/Resources/image/Report_3_df.png)

3. **Summary**: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

- - -

## Rubric

[Unit 21 Homework Rubric](https://docs.google.com/document/d/1SLOROX0lqZwa1ms-iRbHMQr1QSsMT2k0boO9YpFBnHA/edit?usp=sharing)

- - - 

© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.	

