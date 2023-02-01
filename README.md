# YouTube Comments Project

Sentiment Analysis is a NLP technique that is often used to determine whether text is Positive , Negative , or Neutral. The purpose of this project was to perform a sentiment analysis on YouTube comments. I was curious how the mean/median sentiment of comments for a video might interact with other video metrics such as Video Views and Total Comment Count.

I used a RoBERTa-base model trained on 124M posts and fine-tuned for sentiment analysis. [Model Used](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest)

## Project Features
- I created Word Clouds for both Positive and Negative sentiment comments
- I analyzed the confidence of the model. (Was the model more confident in predicting a particular sentiment?)
- Text cleaning (removing stop words/punctuation, word tokenization, lemmatize, finding and removing abnormally long comments)
- Lots of visualizations!



I created an interactive Tableau dashboad that can be viewed at:
[Tableau Dashboard](https://public.tableau.com/views/SentimentAnalysisDashboard_16694102080060/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

Check out my brother's YouTube Channel at:
[Stevie Sells](https://www.youtube.com/c/steviesells)
