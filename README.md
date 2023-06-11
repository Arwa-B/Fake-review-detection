# ChatGPT-Fake-It
## Data Collection Process
ChatGPT-Fake-It is a new fake review dataset collected from Google Play and ChatGPT. This dataset contains 6013 English reviews, including 4000 real and 2013 fake reviews. The average review length is around 21 words. The real reviews are scrapped from the Google Play store using Python about the Facebook mobile application. On the other hand, fake reviews are generated using ChatGPT by querying reviews about the Facebook mobile application. The generated fake review data includes positive and negative reviews about Facebook-related features and services, such as posts, photos, and friends. During the data labeling stage, a new column, \textit{class}, is added to ChatGPT-Fake-It where the real reviews are flagged with 1 and fake reviews are flagged with 0.

## Data Features
We extracted the length of the text, percentage of words, and percentage of stop words, and sentiment analysis was applied to give an indicator of whether this review is positive, negative, or neutral.

## Use Cases 
* Fake reviews detection
* Sentiment analysis 
* Text classification 
* Brand Reputation Management
* Topic Modeling

## Summary 
| Metric    | Value |
| ------- | --- |
| Number of Rows     | 6013  |
| Average Text Length    | 20.95  |
| Minimum Text Length   | 5   |
| Maximum Text Length   | 124  |
| Words Percentage   | 25.59  |
|     Stopwords Percentage   | 0.47  |
