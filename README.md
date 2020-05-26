# Exploring HackerNews Posts
This project is going to work with a data set of submissions to a popular technology site, Hacker News.

Hacker News is a site started by the startup icubator Y Comabinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result

In this project, the data set has been reduced from 300,000 rows to 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions.

Specifically posts whose titles begin with either __*Ask HN*__ or __*Show HN*__. Users submit __*Ask HN*__ posts to ask the Hacker News community a specific question. Below are a couple examples:

* __*Ask HN*__: How to improve my personal website?
* __*Ask HN*__: Am I the only one outraged by Twitter shutting down share counts?
* __*Ask HN*__: Aby recent changes to CSS that broke mobile?

Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting. Below are a couple of examples:

* __*Show HN*__: Wio Link ESP8266 Based Web of Things Hardware Development Platform'
* __*Show HN*__: Something pointless I made
* __*Show HN*__: Shanhu.io, a programming playground powered by e8vm

This project will compare these two types of posts to determine the following:

* Do __*Ask HN*__ or __*Show HN*__ receive more comments on average?
* Do posts created at a certain time receive more comments on average?

\* The data set can be found here https://www.kaggle.com/hacker-news/hacker-news-posts
