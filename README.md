# DATASET
The data for our dataset was gathered solely from real-world sources. The dataset "Budget2024" was constructed using Twitter data. To assess the success of the Indian government, we chose to focus on the Indian budget because it was trending on Twitter and tweets were readily available. The tweets about the recently released Indian Government Budget 2024 on February 1, 2024, were collected using the Twitter API. The dataset contains 10328 tweets from January 29th, 2024 to February 19th, 2024.
# Steps to collect data
To access data from the Twitter API using Python, follow these instructions.
1. Get Twitter API access: An API key and authentication tokens are required to send any type of request to the Twitter API. To accomplish this, we must first apply for and get approved for a Twitter developer account. Once accepted and approved, a project can be built and linked to a sample application. This app will send the Authentication Token (Bearer Token), which is special and confidential and used for subsequent authentication, as well as the API Key.
2. Retrieve data from Twitter API: Python has numerous methods for retrieving data from the Twitter API. The "tweepy" Python library can be used to connect to and retrieve data from Twitter's API.
3. Authenticating with the credentials: To access to the API, use the given API Key and Authentication Token.
4. Keywords: Set the search parameters and gather Tweets.
5. Generate dataset: Using a pandas dataframe, create a dataset using the properties of tweets retrieved from the Twitter API.
