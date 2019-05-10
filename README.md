## AV-Mahindra-DataOlympics

![title](mahindra_.jpg)

## About Club Mahindra DataOlympics

Club Mahindra presents DataOlympics in association with Analytics Vidhya. DataOlympics reflects the data-driven culture we have in Club Mahindra where we take up the most critical and impactful business challenges and try to solve them using data insights and advanced predictive models. In our journey to become a data-driven decision making organization, we invite you to DataOlympics, our flagship hackathon to identify the best talents in the industry to work on challenging business problems.

The top performers will get an opportunity to interview with Data Science team at Club Mahindra. The team has so far developed and successfully deployed wide-range of machine learning and deep learning models like resort recommendations for members, prediction of booking cancellation to improve member experience, lead conversion propensity and many more are in the pipeline. DataOlympics is our endeavour to invite the passionate Data Scientists and Engineers to get a feel of what it looks like solving an RoI driven business problem.
Seize this unique opportunity to be part of our team, who do Data Science while they travel & have fun in the world’s best resorts!


## Problem Statement

Food & Beverages Spend Prediction in Club Mahindra Resorts
Club Mahindra (Club M) makes significant revenue from Food and Beverages (F&B) sales in their resorts. The members of Club M are offered a wide variety of items in either buffet or À la carte form. Following are some benefits that the model to predict the spend by a member in their next visit to a resort will bring:
1.	Predicting the F&B spend of a member in a resort would help in improving the pre-sales during resort booking through web and mobile app
2.	Targeted campaigns to suit the member taste and preference of F&B
3.	Providing members in the resort with a customized experience and offers
4.	Help resort kitchen to plan the inventory and food quantity to be prepared in advance
Given the information related to resort, club member, reservation etc. the task is to predict average spend per room night on food and beverages for the each reservation in the test set.
 
# Data Description

**train.zip**

train.zip contains train.csv and data_dictionary.csv.
•	train.csv contains the training data with details on a set of reservations with the average spend per room night
•	Data_Dictionary.xlsx contains a brief description of each variable provided in the training and test set.
 
**test.csv**

test.csv contains details of all reservations for which the participants need to predict the average spend on FnB per room night
 
**sample_submission.csv**

sample_submission.csv contains the submission format for the predictions against the test set. A single csv/zip needs to be submitted as a solution.
 
## Evaluation Metric
Submissions are evaluated on 100 * Root Mean Squared Error (RMSE) on the variable amount_spent_per_room_night_scaled
