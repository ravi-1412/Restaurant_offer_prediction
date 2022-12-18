# Restaurant_offer_prediction
kaggle competition conducted by IIT madras on Restaurant offer prediction

## PROBLEM STATEMENT 

The data is collected through a survey to understand the driver's behavior regarding their preference for discount/offer for dining/takeaway.
The researcher collected these data by providing different scenarios to various users.

Example Scenario: You are driving from IIT Madras to Chennai Airport along with your family and you get an offer (10 percent discount on the bill) 
from the famous Chinese restaurant in Guindy. 
Will you avail of the offer while traveling?

Along with the user response, some basic information about the users is collected.

EVALUATION METRIC 

The evaluation metric for this competition is Mean F1-Score.

Submission Format
For every author in the dataset, submission files should contain two columns: id and Offer Accepted. Offer Accepted should be a string (Yes/No).
The file should contain a header and have the following format:

AuthorId,DuplicateAuthorIds
0,Yes
1,Yes
2,No


## STEPS TAKEN IN KAGGLE MACHINE LEARNIING PROJECTS COMPETITION 

STEP 1. LOADED DATA SET
STEP 2. DIVIDE INDEPENDENT FEATURE VARIABLE(X) AND DEPENDENT VARIABLE(Y) 
STEP 3. FINDING CORELATION BETWEEN INDEPENDENT FEATURE VARIABLE(X) AND DEPENDENT VARIABLE(Y) USING HEAT MAP
STEP 4. FINDING NULL VALUES
STEP 5. FINDING DATA INFORMATION LIKE DATA TYPE AND ITS COUNT
STEP 6. FINDING OF NUMERICAL COLUMNS AND CATEOGORICAL COLUMNS 
STEP 7. PREPROCESSING OF DATA BY APPLING ONEHOTCODING ON NUMERICAL COLUMNS AND LABEL ENCODING ON CATOGORICAL COLUMNS 
STEP 8. FEATURE SELECTION USING RFE AND TRAINING THE DATA WITH RANDOM FOREST CLASSIFIER 
STEP 9. HYPER PAREMETOR TUNING TO INCREASEING THE REQUIRED SCORE 
STEP 10. LOADING OF TEST DATA
STEP 11. DONE PREPROCESSING STEPS SAME AS DONE IN TRAINING DATA
STEP 12. PREDICTING ON TEST DATA  





