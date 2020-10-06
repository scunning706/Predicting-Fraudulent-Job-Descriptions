# Predicting-Fraudulent-Job-Descriptions

- **Data Set:** [job descriptions dataset](https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction) 

Our goal in this notebook is to explore which columns have the highest correlation with the column `fraudulent`. Moreover, we will investigate if there are unique column values in which these values have a high likelyhood of being attributes of fraudulent jobs. The data set also has lots of text data, and we will be analyzing which words are indicators of a job posting being fraudulent using TF-IDF and a simple logistic regression model. We will also make use of the other attributes by using a K-nearest neighbors model to predict whether a job posting is fake. Overall the mission of this work is to provide a recommendation to executives at a company who are considering creating a branch of the business which uses software to predict fraudulent job postings. We achive this by advising them on what atrributes have the strongest correlation, and share our preliminary results from our models.  

Overall our intial analysis led us to find fraudulent jobs appearing largely in the Oil & Enery Industry, and in Houston, TX. This is actually pretty fitting as Houston has a giant Oil & Energy sector. We also saw over 50% of fraudulent jobs as Full-Time positions, that are entry  level and only require a high school education. 

When creating models it was difficult to be good at predicting fraudulent jobs as our data set was highly imbalenced and we had limited training data. 

Looking at our results over all, we feel it would be more beneficial  to share "flags" with job seekers and to be cautious before sharing personal information. Where job seekers can still flag suspicious jobs, and when more data is acquired a better model could then be used. 
