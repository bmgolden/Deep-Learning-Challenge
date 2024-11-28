# Deep-Learning-Challenge

## Overview 

The principal purpose of creating, compiling, executing, and testing this neural network model is to be able to implement the findings into the central workflow of the nonprofit foundation Alphabet Soup, to benefit the business team's ability to decide which applicants to support to achieve the highest chance of success in their subsequent startups. The business team hopes to be able to employ this machine-learning model to create binary classification outcomes to support their future decision-making.  The model was based on vast historical and categorical data, which was transferred and tested into the model classifying outcomes as successful or unsuccessful, to predict new opportunities for better allocation of resources. 

## Results

### Data PreProcessing 

Target Variables: The distinct target variable in which the model hopes to predict is the success, or unsuccess, of the potential venture, which in this case is the “Is_Successful” column of the dataset. This binary variable is dropped during the preprocessing process to train and test the neural model for future applications. 

Feature Variables: All of the other variables present in the dataset such as “Application_Type”, “Classification”, “Income_Amt”, and “Organization”, as well as a few others are used and converted to binary by way of the get dummies command, known as one-hot encoding, for the training of the model. 

Removed Variables: The two removed variables are the “EIN” and “NAME” columns as they are only descriptive identification columns and are not essential during the construction of the neural model. 

### Compiling, Training, and Evaluating the Model

Network Model: When creating the model, I started with two hidden layers consisting of 80 and 30 neurons, respectively. As for the activation function I chose the “relu” function for both of the hidden layers and the “sigmoid” function for the output layer, which also consisted of one neuron for binary classification. The activation layers and number of neurons were chosen for simplicity in hopes of identifying patterns and repetitions that are prevalent within the data and to ensure non-linearity. 

Model Performance: Initially I was not able to reach the target model performance, but I was close as I was hovering around 72% below the targeted 75%. After multiple attempts and various changes to optimize performance, I was not able to get to the target accuracy percentage. 

Steps to Improve Performance:  I applied numerous optimization techniques over the three attempts in which I tried to improve performance and efficiency. I initially began by trying to change the number of columns I dropped to alter the one-hot encoding aspect while simultaneously altering the bins of the classification and application values feature variables to decrease the variability. I also tried changing the number of layers, number of neurons, and the activation functions to no avail. 

## Summary

After four times trying to attain the targeted performance, I was unsuccessful, but I did attain an accuracy of 73%.  I was not able to meet the standards desired by the business team when trying to classify prospective startups in their future success. Other types of machine learning may be better suited for binary classification such as Random Forests, which historically manipulate categorical data successfully which may apply to this specific situation posed by the foundation. In conclusion, with more testing, improvements, and better data preprocessing this model can be potentially implemented by Alphabet Soup as a tool that may help in identifying future ventures, as long as it is not the sole determinant of deciding whether or not to invest. 
