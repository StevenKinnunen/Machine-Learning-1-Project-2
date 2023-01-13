# Machine-Learning-1-Project-2
Class project to predict flight delay status

BIA 5302 – Fall 2022
Project 02 (20%)

Instructions:
• This assignment is to be completed in groups.
• Please be careful about the due date
• The solutions must be submitted via Blackboard through the assignment’s link.
• The paper must be properly formatted in IEEE format.
• Include all related files (e.g. word file, Latex, .ipynb file, and dataset.csv, if any)
• Any feedback/issue on the Assignment grades should be within a week after grading, a clear email (use Blackboard email please).
• A zero-tolerance policy regarding plagiarism and cheating is in effect.

Requirements: The file FlightDelays.csv contains information on all commercial flights that departed the Washington, D.C., area and arrived in New York in January 2004. For each flight, there is information on the departure and arrival airports, the distance of the route, the scheduled time and date of the flight, and so on. The variable that we are trying to predict is whether a flight is delayed. A delay is defined as an arrival that is at least 15 minutes later than scheduled. 

This assignment has three phases: 

A. Data Preprocessing

  1. Data Reduction: Reduce the number of predictors using the necessary operation (domain knowledge, correlation matrix, etc.). Store the result of this step in a new file “FlightDelaysTrainingData.csv” 
  
  2. Data Exploration stage: Make a copy to the “FlightDelaysTrainingData.csv” file and rename it to “FlightDelaysDataExploration.csv” and use it to provide data summarization using four different Pivot tables to highlight different facts about the database. 
  
  3. Data Conversion: Some of the algorithms don’t comply with numerical data. The non-numerical data in the database is required to be converted. You need to provide a reference table for the transformed data. 

B. Model Building Use the “FlightDelaysTestingData.csv” data file to build models based on: 

  1. Naïve Bayes (NB) model. 
  
  2. Classification and Regression Tree (CART)
  
  3. Logistic Regression. 


Ideally, the above-mentioned algorithms should work with the following data types:

NB: Categorical
CART: Both
Logistic Reg: Categorical 

C. Use Testing Data Make up five new rows (instances) of data and store them in a new file “FlightDelaysTestingData.csv”.
