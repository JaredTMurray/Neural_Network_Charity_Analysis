# Neural_Network_Charity_Analysis
Module20 Neural Networks
## Overview
---
Fot this assignment, I will create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. I will use a CSV that contains more than 34,000 organizations that have received funding from Alphabet Soup business over the years. There are three technical analysis deliverables as follows:

- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaluate the Model
- Deliverable 3: Optimize the Model


## Results
---
- Deliverable 1: Preprocessing Data for a Neural Network Model
- To Preprocess the Data, I imported csv file charity_data. I then, used "EIN" and "NAME" to drop non-beneficial columns. To Determine the unique values of each column, I generated application_cat as a categorical variable. To visualize the dataset, I used the column APPLICATION_TYPE to plot the data for the graph based on density. See graph below
- To Create a OneHotEncoder instance, I fitted and transformed the OneHotEncoder in the variable encode_df, which I then placed into a dataframe of said name. Afterwards, I merged one-hot encoded features and dropped the originals. See image below

- Deliverable 2: Compile, Train, and Evaluate the Model
- To compile the model, I first defined, deep neural net, by using the number of input features and hidden nodes for each layer. See image below. 
- The model was compiled and trained to fit 100 epochs. 
- The evaluation of the model using the test data resulted in the following
- 268/268 - 0s - loss: 0.0489 - accuracy: 0.9900 - 396ms/epoch - 1ms/step
Loss: 0.04886231571435928, Accuracy: 0.989970862865448

- Deliverable 3: Optimize the Model
## Summary
Deliverable 4: A Written Report on the Neural Network Model (README.md)
Deliverable 4: A Written Report on the Neural Network Model (30 points)
You will earn a perfect score for Deliverable 4 by completing all requirements below:

Structure, Organization, and Formatting
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt)
Each section has a heading and subheading (2 pt)
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis
The written analysis has the following:

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
Results:

There is a bulleted list that answers all six questions (15 pt)
Summary:

There is a summary of the results (2 pt)
There is a recommendation on using a different model to solve the classification problem, and justification (3 pt)
