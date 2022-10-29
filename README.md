# Visualize-Chatbot-Data-to-Inform-Business-Decisions
The Customer Support on Twitter dataset, which includes tweets, replies, and author IDs for both corporations and enquiring individuals, was examined. Chatbots are employed to assist with customer service, and this dataset will provide details on the languages utilized, traffic statistics on a yearly and monthly basis, and top users, to mention just some. There are 7 columns and 2,811,774 rows in this dataset.

## Columns Identification
- 'tweet_id' = identifies the tweet assigning it a specific number
- 'author_id' = identifies the author of the tweet. Company tweets will display the company name, and individual tweets will display a specific id number
- 'inbound' = boolean value that determines who is reaching out to the company account. If TRUE, the individual is reaching out and tagging the company account. If FALSE, the company account is replying/tagging the customer
- 'created_at' = date and time when tweet was published
- 'text' = body of text of the tweet
- 'response_tweet_id' = references the tweet_id that it's replying to
- 'in_response_to_tweet_id' = a specific ID to be referenced when the tweet is being replied to

## Background Information
A chatbot is a computer program that uses artificial intelligence (AI) and natural language processing (NLP) to understand customer questions and automate responses to them, simulating human conversation. Chatbots works on the data you feed into them, and this set of data is called a chatbot dataset. You can divide the dataset into two categories. One is questions that the users ask, and the other is answers which are the responses by the bot.

The Twitter Chatbot is utilized to converse with users. This AI-based tool can assist a large number of individuals by responding to their inquiries about pertinent matters. NLP is applied with the Twitter Chatbot Data to make it machine-understandable using particular algorithms. To help machines interpret the tweets' language or sentences, more info is supplied to each one. 

## Situation
Analyze the given data set from Twitter based on a chatbot with several different companies.
## Task
Implement Data Exploration, Data Visualization, and Data Cleaning methods to figure out which company is the most interactive with their customers.
## Action
Layed out a blueprint on how I would be able to connect and analyze the top 10 companies. Programmed the graphs and charts to display the information. 
## Result
Discovered Amazon has been the most interactive with their customers. Followed by Apple, then Uber. Spotify was very close with Uber. Delta is over Tesco on Monday, Tuesday, Thursday, Friday, Saturday and Sunday. Tesco is over Delta only on Wednesday. American Air is over T-Mobile on Monday, Thursday, Saturday and Sunday. T-Mobile is over American Air on Tuesday, Wednesday and Friday. Comcast is over British Airways on Monday, Tuesday, Wednesday, Friday, Saturday and Sunday. British Airways is over Comcast only on Thursday. Overall, Amazon has the highest interactive rate with the users. Also, this applies to each and every company, as the weekend approaches, the number of tweets decline by a majority.
