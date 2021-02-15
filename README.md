# Reddit Data Analysis


## **Introduction:**

Following document shows the comparison of two subreddits: emacs and vim. The focus is to learn and analyze patterns of contributors's behavior between two editors. 
Specifically, I compare number of posts, number of comments, score, distinct authors, upvotes & frequent changes, original content frequency between the two posts and comments of the two editors.

---

## **Execution:**

The data is collected by using PRAW (The Python Reddit API Wrapper) Library & Pushshift API. I created a function that will take time frame and subreddit name as an input and download the data in the form of CSV file. 
### Following features are extracted : 
The author details, title, ratio of upvotes, score (upvote - downvote), original content, edit activity (Yes/No), the unique identification, url of post, number of comments, body & the creation date for each post between 01-01-2020 to 03-31-2020 are extracted & saved into .csv files. 

---

## **Executive Summary:**

While the detailed charts comparing distributions of various metrics listed above are checked into repository, I provide a brief summary in the below table. 
In most aspects, both the editors are very comparable, with Emacs showing a slightly more popularity/level of engagment with 226 more posts, 291 more comments, and 34 additional contributors between the period of three months. However, interestingly, Vim had a higher average of comments (10) on posts as compared to Emacs (9) indicating a little bit more depth to the conversation around Vim. While Emacs had a higher upvote ratio (0.91) as compred to Vim (0.75), the average score for Emacs was lower (15.34) as compred to Vim (25.08), suggesting that there were also significantly higher downvotes for Emacs posts as compared to Vim.   

There are 672 unique authors for 1330 Emacs posts (Num posts per author ratio: 1.97) and 638 unique authors for 1104 Vim posts (Num posts per author ratio: 1.73) indicating that Emacs has higher posts per author. In addition, there are 23 authors who have contributed to both Emacs and Vim posts. 

Emacs also has higher percentage (19.02%) of posts edited as compared to Vim (15.67%) potentially indicating that more Emacs authors refine their posts with clarification or update the posts with a summary of discussion as compared to Vim. 

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
