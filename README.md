# DATASET
The data for our dataset was gathered solely from real-world sources. The dataset "Budget2024" was constructed using Twitter data. To assess the success of the Indian government, we chose to focus on the Indian budget because it was trending on Twitter and tweets were readily available. The tweets about the recently released Indian Government Budget 2024 on February 1, 2024, were collected using the Twitter API. The dataset contains 10328 tweets from January 29th, 2024 to February 19th, 2024.
# Steps to collect data
Follow these steps to retrieve data in Python from the Twitter API.
1. Get Twitter API access: To send any kind of request to the Twitter API, you must have an API key and tokens for authentication. In order to accomplish this, we must apply for access by submit an application for and receive approval for a Twitter developer account. Once it is accepted and approved, a project can be created and linked to a sample application. The Authentication Token (Bearer Token), which is special and confidential and used for subsequent authentication, and the API Key will be sent by this app.
2. Retrieve data from Twitter API: Python provides several ways to retrieve data from the Twitter API. The "tweepy" Python package can be used to establish a connection to and retrieve data from the Twitter API.
3. Using the credentials to authenticate: Use the provided API Key and Authentication Token to authenticate and establish a connection with the API.
4. Keywords: Establish the parameters for the search and gather the Tweets.
5. Generate dataset: Using a pandas dataframe to generate a dataset by utilising the attributes of the tweets obtained from the twitter API.
