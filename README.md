# Reddit - NLP Project
## About the project: 
Our goal for this project is to explore reddit.com and find two topics with enough comments. These topics can be different and also have some kind of relationship. Then build an NLP model to classify comments and returns which topic that comment belongs to. 

For our project we selected the “love” and “ask reddit” as topics and then developed an API to get data for both topics. We collected around 5000 comments for both topics. 

After collecting the data, we explored the data and find out there are some nan cells and some [removed] cells that people might have removed their comments, we could not delete all because we were going to lose lots of data. Therefore, we replaced both with an empty cell, so we can combine the subject with the comment. Then we dummied our topic column and checked the data frame to see if there is any other cleaning needed. 

Then we tokenized our data with both Count Vectorizer and TFDIF with different tuning parameters.  We used Naïve Bayes and Logistic Regression with both tokenized data. 

Following are the scores on each model which shows the accuracy of our model on train and test data:




CV Lr Train Score :0.984
<br />
CV Lr Test Score  :0.939
<br />
<br />
CV nb Train Score :0.927
<br />
CV nb Test Score  :0.924
<br />
<br />
TIFDF Lr Train Score :0.952
<br />
TIFDF Lr Test Score  :0.931
<br />
<br />
TIFDF nb Train Score :0.941
<br />
TIFDF nb Test Score  :0.924
<br />
<br />
### Workflow:
Flowing are the steps we took for this project to get the result: 


**Defining the Data Science Problem**
<br />
**Identify and select the topics from reddit website**
<br />
**Web scarping and data collection for the topics we selected**
<br />
**Exploring the Data and Data Cleaning**
<br />
**Feature Engineering and Model Selection** 
<br />
**Implement Models and tuning the parameters**
<br />
**Evaluating the Models**
<br />
**Select the Best Model**
<br />

### Project's Files:
The follwoing are project files, codes, and presentation. 

- [Project Code Phase I](./Project_3_NLP_Phase_I.ipynb)
- [Project Code Phase II](./Project_3_NLP_Phase_II.ipynb)
- [Project Presentation](./Project_3_Presentation.pdf)
- [Data Set](./database.csv)
- [Working Data Set](./raw_df.csv)

<br />
<br />
<br />

[Have Question? ](https://roymansoor.github.io/)