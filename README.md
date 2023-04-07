# Lead_Score_Prediction
Problem: Lead Scoring Model

Selling something is not an easy task. A business might have many potential customers, commonly referred as leads, but not enough resources to cater them all. Even most of the leads won’t turn into actual bookings. So there is a need for a system that prioritises the leads, and sorts them on the basis of a score, referred to here as lead score. So whenever a new lead is generated, this system analyses the features of the lead and gives it a score that correlates with chances of it being converted into booking. Such ranking of potential customers not only helps in saving time but also helps in increasing the conversion rate by letting the sales team figure out what leads to spend time on.

Here you have a dataset of leads with their set of features and their status. You have to build a ML model that predicts the lead score as an OUTPUT on the basis of the INPUT set of features. This lead score will range from 0-100, so more the lead score means more chances of conversion of lead to WON. NOTE: The leads with STATUS other than ‘WON’ or ‘LOST’ can be dropped during training.

Dataset Link- https://drive.google.com/file/d/1nZIUn8CND8GOUp6bB2y4dI2Q8LQkBfqc/view?usp=share_link

Conclusions:
The best metrics we are getting from XGboost and considering XGboost as our final optimal model:
1. Accuracy: 99%
2. Recall: 0.99
3. Precision: 0.99
4. F1 SCORE: 0.99
5. AUC-ROC: 0.99
