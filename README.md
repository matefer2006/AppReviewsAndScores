# AppReviewsAndScores

Classification of any app's Google Play store and iOS store reviews using OpenAIs API.

Process is divided in 5 stages:

1- Extract reviews from iOS store using BeautifulSoup library

2- Extract reviews from Google Play store using google_play_scraper

3- Combine both datasets

4- Use gpt-3.5-turbo-instruct model via OpenAIs API to classify each review in Positive, Neutral or Negative

5- Upload results to database
