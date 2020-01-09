# Exploring hacker news post
* This project is the final assignment of the 'Python for Data Science: Intermediate' course on Dataquest.io. 
 
 In this project we'll analyze Ask and Show posts on Hacker News and analyze which posts created at what hour receive the most comments

Guided Project: Exploring Hacker News Posts
This is the guided project for the 'Python for Data Science: Intermediate' course of Dataquest.

In this project, we'll work with a data set of submissions to popular technology site Hacker News.

You can find the data set at https://www.kaggle.com/hacker-news/hacker-news-posts, but note that it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. Below are descriptions of the columns:

- id: The unique identifier from Hacker News for the post
- title: The title of the post
- url: The URL that the posts links to, if it the post has a URL
- num_points: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
- num_comments: The number of comments that were made on the post
- author: The username of the person who submitted the post
- created_at: The date and time at which the post was submitted

We're specifically interested in posts whose titles begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question, such as 'Ask HN: How to improve my personal website?'
Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting, such as 'Show HN: Shanhu.io, a programming playground powered by e8vm'.

We'll compare these two types of posts to determine the following:
- Do Ask HN or Show HN receive more comments on average?
- Do posts created at a certain time receive more comments on average?
