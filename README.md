# Taylor’s triumph: Social Media Analysis of the 2023 person of the year
### Overview
This project focuses on analyzing Taylor Swift's triumph in 2023 through social media platforms, particularly Reddit. The analysis delves into the reasons behind Taylor Swift being named the TIME Person of the Year and explores the impacts of her recognition. The project utilizes data from the Taylor Swift subreddit to understand the evolution of her fan community, sentiment analysis, and key topics associated with the iconic pop star.

### Data Collection
Reddit API was leveraged to extract data from the Taylor Swift subreddit in 2023.
Two datasets, "hot" and "top," were obtained to capture discussions and posts with high community approval.
Extracted variables include subreddit name, post title, text content, upvote ratio, upvotes, downs, score, author, publication date, post identifier, and link.
### Data Preprocessing
Natural Language Toolkit (NLTK) was used for intricate language processing tasks.
Text data underwent preprocessing to refine and structure content for advanced analyses.
The "TaylorSwift" subreddit in 2023 served as the primary data source for the analysis.
### Social Network Analysis
Metrics and community detection techniques were applied to understand the structure and dynamics of Taylor Swift's fan base.
The analysis aimed to uncover insights into the fan community's interactions and connections.
### Social Content Analysis
Sentiment analysis was conducted to gauge public perception and feelings towards Taylor Swift.
Emotion analysis and Named Entity Recognition were employed to delve deeper into the content and sentiments expressed in the subreddit posts.
### Conclusion
The project aims to provide a comprehensive analysis of Taylor Swift's impact in 2023, beyond her musical achievements. By exploring social media data and sentiment analysis, the project sheds light on the reasons behind her recognition as the TIME Person of the Year and the excitement generated within her fan community.

This directory is organized as follows:
- PDF (containing the report and presentation)
- Data
- Code

The Code folder includes five notebook files, organized as follows: the first pertains to the collection of data, with the output stored in the Data folder containing the utilized datasets; the second focuses on preprocessing; the third on Social Network Analysis (SNA); the fourth on sentiment analysis; and the fifth on Named Entity Recognition (NER).

We recommend using the provided data, as the data collection code requires a secret token for the Reddit API. 
The authors of this project are Giulia Beccaria and Lorenzo Lobosco.

Result: 6.5/8
