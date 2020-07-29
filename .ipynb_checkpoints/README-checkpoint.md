# Hacker News Post Statistics

**Date:** 29-07-2020

Analyzing data from Hacker News to find the best time for users to submit posts. The focus is on posts that start `Ask HN` or `Show HN`.


`hacker_news.csv`: The dataset we're using to analyze the post data. It's been reduced from around 300K rows to about 20K rows by removing all posts that do not have any comments, and then randomly sampling from the remaining submissions. You can find the original dataset [here](https://www.kaggle.com/hacker-news/hacker-news-posts).

`HNPostStats.ipynb`: the jupyter notebook containing the code.