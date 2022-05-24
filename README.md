# Project 3: Web APIs & NLP

## Executive Summary

### Introduction 
Chewie is a ten-pound rescue pup who loves everyone and plans to be a therapy dog once the AKC Canine Good Citizen test is passed. 


### Problem and Goals

__Goal:__ Build a classification model that can be used to identify Service Dogs vs Dog Training <br>

Service dogs require a lot of training. 

- What are the classification opportunities between the subreddits for Service Dogs and Dog Training? 
- How can those classifications help to predict training opportunities for service and other dogs?


### Data Dictionary

Features used listed below:
| **Feature**      | **Type** | **Dataset** | **Description**                                           |
|------------------|----------|-------------|-----------------------------------------------------------|
| **subreddit**    | _object_ | df          | Subreddit Name (instance of Subreddit)                    |
| **title**        | _object_ | df          | Title of submission                                       |
| **selftext**     | _object_ | df          | Selftext of a submission (an empty string if a link post) |
| **score**        | _int64_  | df          | Total points for a submission                             |
| **num_comments** | _int64_  | df          | Number of comments on the submission                      |


### Model Findings

- Overall, the Logistic Regression model was the best model to identify Service Dogs vs Dog Training Subreddits.
- The SVM: C-Support Vector Classification model could also be used.


### Recommendations

__Implications:__ <br>
- Logistic Regression model was most accurate
- Did not help predict training opportunities for service or other dogs

__Next Steps:__ <br>
- Classification opportunities could be to look more into the most common words and compare the differences between each Subreddit
- Next steps would include specifically looking for training theories and pedagogy related words
