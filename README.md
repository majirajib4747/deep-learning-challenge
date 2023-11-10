Overview :

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

Data Preprocessing

Target Variable : IS_SUCCESSFUL
Feature Variables are : 

APPLICATION_TYPE            
AFFILIATION                 
CLASSIFICATION              
USE_CASE                     
ORGANIZATION                 
STATUS                       
INCOME_AMT                  
SPECIAL_CONSIDERATIONS       
ASK_AMT 

Below Variables been removed : 
EIN","NAME

Compiling, Training, and Evaluating the Model : 

I had created 1 Model and tries to tune hyper paramenter to get the better accuracy rate. 

In first Model : I have 2 Layers ( with 80 and 30 Neurons) - Bith have Relu Activation . Output Layer has Sigmoid Activation. In this momodel loss is 55 % and Accuracy is 72%. 

Optimization Model 1 Has 3 Layers ( Extra 3rd Layer with 30 Neurons). It has same Accuracy and Loss Optimization Model 2 has greater epochs=150 ( from 100) . Almost same Accuacy and Loss. Optimization Model 3 has another extra Layer ( with 30 Neurons) , but still has same Accuracy and Loss. All 4 Model been loaded to GIT. Summary : As this dataset has many features, decision Tree might give better result
                  
