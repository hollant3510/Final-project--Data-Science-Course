# Final-project--Data-Science-Course


# instructions for final submission (Final project 2 jupyter file)

Overview
For our final project, we will be analyzing data from a social issue. At this point, you have an approved dataset and social issue and now it is up to you to present the results of your analysis through digital form. This presentation should be in a jupyter notebook and treated as if you are presenting it to the CEO of your company (or if you prefer...you are the CEO and you are presenting it to your employees).

You will be asking 4 questions of your data. 3 you have already come up with and 1 additional as described in 'requirements'.


Requirements
1) overview of your project including a background on the dataset and the questions that you are asking your data. This should include why you are asking the question, any challenges that you expect to face and a general overview of the methodology you will be using. This also should include where you got the data and any required background.
2) thorough analysis of the dataset including data types, size of file, columns, etc.
3) imputing of data where appropriate
4) answering of the 3 questions proposed during the "Assignment 5" with written explanation for each step that you take. This explanation should talk about the methodology you are using and why you are using it. Include any visual guidance that you use (e.g. heatmaps).
5) answering a 4th question that requires additional data added to or created for your dataset. As a data scientist, often times you will have to augment your existing dataset. In order to achieve requirement 5, you will need to augment your data by either (a) pulling in data from an external dataset or (b) creating a new column from existing data in your dataset then answering a question about it chosen from any of the question categories. This step includes the requirements from step 4.
6) visualizations that help explain your results from requirements 4 and 5.
7) written conclusions for each of the questions that you answered. This should explain your results, if they are good, or if they are bad, why and how you would improve.

Rubric
(20 points) The project is presented in a jupyter notebook in a professional manner. This includes an introduction describing the dataset, the source of the dataset, why you picked the dataset, etc. All sources (of code, files, etc.) should be cited. The flow of the project is consistent with the requirements and conclusions are thorough.

(10 points) Thorough analysis of the dataset is done prior to any questions being answered.

(20 points / 5pts each) The project has 4 questions that fit into the "Question" list below. The questions are inquisitive and challenging and extract information from the dataset.

(10 points) The dataset is augmented for the 4th question.

(20 points / 5pts each) The work done to answer each question is logically explained and written with notes to describe what is being done, how it is being done, etc. such that the reader could understand the flow of the presentation by simply reading the respective text.

(40 points / 10pts each) The work done to answer each questions utilizes the techniques and tools we have learned in class. Where accuracy is required, it should be shown how the model was improved in an iterative manner with written explanation to complement.

(20 points / 5pts each) Visualizations are provided for the conclusion of each question as well as in the work to derive the conclusion where appropriate.

(20 points / 5pts each) A thoroughly written conclusion for each question is written explaining the results and how they can be improved if applicable.

(10 points) An overall conclusion recapping the presentation and anything learned from the information derived.

Content
The content should be written to an audience that has some understanding of data science principles. It is not expected that you're results are accurate but it is expected that you attempt to build sophisticated models. For example, if you build a logistic regression model and it is only 50% accurate then you should show that you made multiple attempts and adjustments to improve your model. You should then explain what limitations your model has...why you think it is not working...and how you think it could improve.

The content should be formatted in a professional manner. This means code should be commented where appropriate, attribution should be given if you use someone else's images, data, etc.

Questions

WHO, WHAT, WHERE, WHEN?

Example Questions
Which owner has the most locations taller than 120 feet?
What year had the most grateful dead songs?
Which state had the most alien sightings?
What mobile device is most of our users using?

Solve Using
Tools like pandas and python

WHAT HAPPENS IF/WHEN?

Example Questions
What happens if we move the "Buy Now" button to the top of the screen?
What happens if we change the price from 9 dollars to 11 dollars?
What happens if we use a person with a happy face vs a sad face?

Solve Using
a/b tests (hypothesis testing)
experimentation
cross validation

CAN WE PREDICT? INFERENCE

Example Questions
What will the price of 3 bedroom house on 7th Ave Brooklyn be in 2025?
What will the price of IBM stock be next month?
How many users will quit our service next month?
Of the people that signed up for our free trial, how many will convert to paid users?

Solve Using
Regression

IS THERE A RELATIONSHIP BETWEEN?

Example Questions
Is there a correlation between time of day and number of purchases at our store?
Is there a correlation between when we hired Lucy and when sales went up?

Solve Using
Regression
Correlation/Covariance

CLASSIFICATION

Example Questions
What is the sentiment of this twitter post?
What type of animal is in this picture?
Was this a legitimate purchase on your credit card or not?
Will this student get into TCNJ?

Solve Using
Classification Algorithms

CLUSTERING

Example Questions
Can we define groups of our customers based on their buying habits?
Are we able to cluster TCNJ students based upon their studying habits?
Are there cohorts of people who use our web app differently?

Solve Using
Clustering Algorithms








# Info for What I aimed to solve (Problem proposal) 
Overview
For our final project, we will be presenting our findings from a dataset surrounding a social issue. We will be answering multiple questions about this dataset from the below list. For this assignment, you will have to find a dataset that involves a social issue and start thinking about the types of hypothesis that you can come up with and questions you would like to explore.

Assignment
Find a dataset involving a social issue that you will use for your final project. Ask 3 questions about this dataset from the list below. Each question must be a different type e.g. all 3 questions CANNOT be a who, what, where, when.

Note that I will approve each dataset for the final project. You may use more than 1 dataset e.g you could use 3 datasets, 1 for each question. Also - we have not yet gone over how to do all of the below questions but we will shortly (at least most of them). Lastly, you are allowed to go outside the scope of tools learned in class with my approval e.g. you may use other machine learning algorithms for prediction/inference.

What to Deliver
1) The url to the dataset that you will be using.
2) The size of the dataset i.e. number of rows and columns
3) The column names of the dataset and their dtypes
4) The 3 questions that you are considering asking

Resources for finding datasets
https://www.kdnuggets.com/datasets/index.html (Links to an external site.)
https://www.springboard.com/blog/free-public-data-sets-data-science-project/ (Links to an external site.)
https://www.forbes.com/sites/bernardmarr/2016/02/12/big-data-35-brilliant-and-free-data-sources-for-2016/#7ef6504fb54d (Links to an external site.)
https://github.com/awesomedata/awesome-public-datasets (Links to an external site.)
https://registry.opendata.aws/ (Links to an external site.)

Questions

WHO, WHAT, WHERE, WHEN?

Example Questions
Which owner has the most locations taller than 120 feet?
What year had the most grateful dead songs?
Which state had the most alien sightings?
What mobile device is most of our users using?

Solve Using
Tools like pandas and python

WHAT HAPPENS IF/WHEN?

Example Questions
What happens if we move the "Buy Now" button to the top of the screen?
What happens if we change the price from 9 dollars to 11 dollars?
What happens if we use a person with a happy face vs a sad face?

Solve Using
a/b tests (hypothesis testing)
experimentation
cross validation

CAN WE PREDICT? INFERENCE

Example Questions
What will the price of 3 bedroom house on 7th Ave Brooklyn be in 2025?
What will the price of IBM stock be next month?
How many users will quit our service next month?
Of the people that signed up for our free trial, how many will convert to paid users?

Solve Using
Regression

IS THERE A RELATIONSHIP BETWEEN?

Example Questions
Is there a correlation between time of day and number of purchases at our store?
Is there a correlation between when we hired Lucy and when sales went up?

Solve Using
Regression
Correlation/Covariance

CLASSIFICATION

Example Questions
What is the sentiment of this twitter post?
What type of animal is in this picture?
Was this a legitimate purchase on your credit card or not?
Will this student get into TCNJ?

Solve Using
Classification Algorithms

CLUSTERING

Example Questions
Can we define groups of our customers based on their buying habits?
Are we able to cluster TCNJ students based upon their studying habits?
Are there cohorts of people who use our web app differently?

Solve Using
Clustering Algorithms


URL https://github.com/jamesqo/gun-violence-data/blob/master/DATA_01-2013_03-2018.tar.gz (Links to an external site.)

Size 239677, 29

Column names and Dtypes

incident_id                      int64

date                            object

state                           object

city_or_county                  object

address                         object

n_killed                         int64

n_injured                        int64

incident_url                    object

source_url                      object

incident_url_fields_missing       bool

congressional_district         float64

gun_stolen                      object

gun_type                        object

incident_characteristics        object

latitude                       float64

location_description            object

longitude                      float64

n_guns_involved                float64

notes                           object

participant_age                 object

participant_age_group           object

participant_gender              object

participant_name                object

participant_relationship        object

participant_status              object

participant_type                object

sources                         object

state_house_district           float64

state_senate_district          float64

dtype: object

 Questions
 
Which congressional district has the most shootings

Can we predict how many killed / injured based on the location

Is there a relationship between week day and shooting

