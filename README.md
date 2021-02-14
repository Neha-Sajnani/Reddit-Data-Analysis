# Reddit Data Analysis


## **Introduction:**

Following document shows the comparison of two subreddits: emacs and vim. The main focus is to identify which subreddit has higher popularity & observe the contributor's behaviour. We define popularity as one having a higher number of interactions on posts based on greater number of comments, score, authors, upvotes & frequent changes.

---

## **Execution:**

Scrapping of the reddit data using PRAW (The Python Reddit API Wrapper) Library & Pushshift API to get the data from a specific duration of date is done. 
### Following features are extracted : 
The author details, title, ratio of upvotes, score (upvote - downvote), original content, edited activity (Yes/No), the unique identification, url of post, number of comments, body & the creation date from 01-01-2020 to 03-31-2020 & saved it into .csv files. 
I have analysed & visualized the data using several graphs like Histograms, Bar charts, Pie charts for better understanding.


---

## **Conclusion:**

Despite having lower number of posts, authors, comments and upvote count, VIM subreddit has more contributor engagement between 01/01/2020 - 03/31/2020 because it has an average of score (25.08) which is significantly higher than that of EMACS (15.34) and comments per post (10).  There are 23 common authors between EMACS and VIM.

The ratio of monthly distribution of posts in both the subreddits is almost the same even if r/emacs has a significantly higher number of posts.

| | Jan | Feb | Mar |
| -----------| ----------- | ----------- | ----------- |
| EMACS | 486 | 411 |  433 |
| VIM | 377 | 351 |  376 |

&nbsp;

The following table shows the brief of findings.

|  | EMACS | VIM |
| ----------- | ----------- | ----------- |
| Number of posts | 1330 | 1104 |
| Number of Comments | 12375 | 12084 |
| Average Comments | 9 | 10 |
| Number of Authors | 672 | 638 |
| Avg upvote ratio | 0.91 | 0.75 |
| Avg Score | 15.34 | 25.08 |
| Percentage of Edited Posts | 19.02% | 15.67% |
