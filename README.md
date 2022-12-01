# Hacker News Posts

## Data set: [Hacker News Posts](https://www.kaggle.com/hacker-news/hacker-news-posts)
Hacker News is a site, where users post stories (known as "posts"), and they vote or comment on other people's stories.

This particular data set is Hacker News posts from September 2015 - September 2016. It includes the following columns:

* `id`: The unique identifier from Hacker News for the post
* `title`: The title of the post
* `url`: The URL that the posts links to, if the post has a URL
* `num_points`: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downbotes
* `num_comments` : The number of comments that were made on the post
* `author`: The username of the person who submitted the post
* `created_at`: The date and time at which the post was submitted

## Ask the following questions:
* Do posts that ask specific questions (i.e., post title begin with `Ask HN`) or posts that share something (i.e., post title begin with `Show HN`) receive more comments on average?
* Do posts created at a certain time receive more comments on average? 

## Materials:
* `hacker_news.csv`: data
* `HackerNewsPosts.ipynb`: data cleaning and analysis