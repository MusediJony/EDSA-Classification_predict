# EDSA Classification predict.

## This Repository is one created for the Classification project by Explore Science Data Academy.

### The project is a competition (Hackathon challenge) held on the Kaggle Data Science community platform, 

The challenge instructs the competitor to classify the sentiment of an individuals tweet based on whether they believe climate change is real or not (historical tweet data). Companies will then use the info in their market research efforts to gauge how their services and products are received by the masses.

https://www.kaggle.com/c/climate-change-edsa2020-21/overview

The metric that was used for this this challenge is the  Macro F1_score with a passmark in relation to your score being above 0.65 (0% achieved if score is below 0.65, 50% achieved if score at 0.65 and 100% achieved for a score of 0.75 and above).

(Bear in mind the challenge is still on going, however, currently my Macro f1_score  = 0.75047...This score is poised to change as the current score is calculated with 80% of the ground truth data set. The final result will be based on the other 20% of the data)

The link above takes you to the actual competition. You can then click on the leaderboard and see my profile at position 24, Jonathan Bashala.

I have built 7 classification models: Linear SVC, SVC, Random forest, AdaBoost, Decision Tree, MultinomialNB and Nearest Neighbours.

I chose the the LinearSVC as the best performing model due to it giving me the highest Macro F1_score out of all the built classification. 

It's also wise to mentioned that the F1_score obtained on the report/notebook is different to that of the F1_score score obtained on Kaggle. This is due to the fact that on the report, cross validation was conducted on the whole train data set as a guide for our predicted values.

#### Explanation of the classes and it's respective sentiment

#### Class - Description

#### 2 : News:    The tweet links to factual news about climate change.
#### 1 : Pro:     The tweet supports the belief of man-made climate change.
#### 0 : Nuetral: The tweet neither supports nor refuse the belief of man-made clmate change.
#### -1 : Anti:   The tweet does not believe in man-made climate change.



 
