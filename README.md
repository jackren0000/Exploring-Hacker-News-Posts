# Exploring Hacker News Posts

**Introduction**
Hacker News is a site started by the startup incubator Y Combinator, where user interactive with posts.
Hacker News is extremely popular among technology and startup groups. Posts
that make it to the top of the forum can receive tremendous views. In this project, we intend to find the best time to make 
a post.

**Dataset**
The dataset we used is the official Hacker News dataset hosted on Kaggle. It includes seven columns: id, title, url, num_points, num_comments, author, and created_at.
We further preprocessed the data by removing all submissions that didn't receive any comments and then randomly sampled from the remaining submissions. We reduced the dataset from almost 300,000 rows to approximately 20,000 rows.

**Methodology**
We categorized the titles into three groups, Ask HN, Show HN, and Others.
Ask HN is where users ask the Hacker News community a question, and Show HN is used for showing the community a project or product. 
Then we calculated the average number of comments received by these categories and determined the best time to post — when authors are most likely to get attention (in the form of comments).

**Results**
We found that between 15:00 and 16:00 EST, which is between 5:00 and 6:00 in Melbourne, there is a higher chance of receiving comments.