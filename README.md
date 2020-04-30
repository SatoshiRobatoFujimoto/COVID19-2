# CoronaVis: A Real-time COVID-19 Tweets Analyzer

The goal of ConronaVis is to use tweets as the information shared by the people to visualize topic modeling, study subjectivity and to model the human emotions during the COVID-19 pandemic. The main objective is to explore the psychology and behavior of the societies at large which can assist in managing the economic and social crisis during the ongoing pandemic as well as the after-effects of it. In this paper, we describe the CoronaVis Twitter dataset (focused on United States) that we have been collecting from early March 2020. We would like to share this data with the hope that it will enable the community to find out more useful insights and create different applications and models to fight with COVID-19 pandemic and the future pandemics as well. 
The paper is available at [arXiv](https://arxiv.org/pdf/2004.13932.pdf)

## Data Description
We are continuously collecting the data since March 5, 2020 and will keep fetching the tweets using [Twitter Streaming API](https://developer.twitter.com/en/docs/tutorials/consuming-streaming-data). We have collected around 700GB of raw data until April 24, 2020 and saved this data as JSON files. However, we dynamically process this data in real-time for the [CoronaVis](https://mykabir.github.io/coronavis/) application. We processed several features from the tweets such as (Tweet ID, Tweet Text, User Location if available, User Type), etc. We will keep collecting the data and update this data repository once in every week. 

### Data attributes
#### tweet_id 
Unique ID of a tweet.

#### created_at 
Creation time of a tweet.

#### tweet_id 

#### tweet_id 

#### tweet_id 

#### tweet_id 