# LogisticRegression_Hackerearth


https://www.hackerearth.com/challenges/hiring/ericsson-ml-challenge-2019/machine-learning/abc-test/

Problem statement

Your tasking is to predict the overall rating of reviews.     

Columns

'ID': Indentificaition Number 
'Place': Startup {1-6}
'location': Location of startup 
'date': Date of review 
'status': Current status with the startup 
'job_title': Position of work at the startup
'summary': Overall summary
'positives': Pros
'negatives': Cons 
'advice_to_mgmt': Comments given by the reviewer to the management
'overall': Overall rating provided by the user {1-5}
'score_1' to 'score_5': Intricate rating with reflects the condition of work at the startup {1-5}
'score_6': Number of likes received by the reviewer for the review 

Full data
Train: train.csv (30336 X 17)
Test: test.csv (29272 X 16)
Solution: submission.csv (29272 X 2)

Data Files: http://hck.re/7gftHn


Data description
Data have been extracted from a website that provides job reviews. The website wants to analyze texts and the corresponding rating that is provided by the user about startups. A research team wants to analyze the liability of the review. In other words, they want to verify whether texts correspond as the same as the score that is provided as the rating for a startup. 
This task helps the website to rank the user's reviews or ratings.   

Evaluation metric

F1-Score

Baseline

LogisticRegression: 40-50% on the test set

Task
You are provided with the reviews that the users have submitted for a company and a few intricate scores. Your task is to predict the overall rating provided by the reviewer.   
