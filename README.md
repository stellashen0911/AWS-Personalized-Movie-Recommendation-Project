# AWS-Personalized-Movie-Recommendation-Project

## Brief about this project

This is a real-time personalized movie recommendations with Amazon Personalize. Amazon Personalize is a fully managed machine learning service that enables developers to build customized recommendation systems. 

In this project, I did 
- Used the Amazon Personalize Interactions and Users datasets and created the interactions_schema for the MovieLens dataset and provides it to Personalize, then upload the data into an Amazon S3 bucket
- Created a Amazon S3 bucket that stores the interaction data, and configured the S3 bucket to allow Amazon Personalize access to the data
- Train the solution version model using the User_Personalization recipe
- Deployed a campaign to make real-time recommendations for user

## Example recommendation result for a specified user

![](https://i.imgur.com/sYuUcty.png)
