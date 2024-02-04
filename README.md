# random_forest_w_python

Project Overview

This project develops a predictive model to identify behaviors that determine active engagement among content creators on our digital platform. Active creators are those who frequently update their profiles, add quality content, and maintain an aesthetically pleasing profile without becoming inactive or churning.

Objective
To pinpoint key actions and metrics that predict active engagement, thereby informing strategies to boost creator activity.

Approach
Data Preparation: Cleaned and prepared a dataset focusing on relevant features for creator engagement.
Modeling: Utilized RandomForestClassifier for its effectiveness in handling complex datasets and imbalanced classes.
Evaluation: Assessed model performance using Accuracy (94.73%) and ROC AUC Score (95.24%).

Key Finding
The most critical predictor of active engagement is save_edit_placeholder, highlighting the importance of profile updates. Frequent profile updates are a key indicator of a creator's active engagement. Insights from the model can guide efforts to encourage more vibrant and sustained creator participation on our platform.

Model Performance
Accuracy: 94.73%
ROC AUC Score: 95.24%
Top Feature: save_edit_placeholder (28.79%)
