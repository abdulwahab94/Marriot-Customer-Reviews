Using NLP, sentiment analysis is carried out on Marriot Hotels Uk to …
…understand the overall customers sentiment towards the hospitality giant. This simple analysis helps senior management and strategy planners to identify the key areas to be addressed and improve the over customers experience which is key to good business. The methodology is as follows:

1- Import the required libraries
2- Web scraping is done by initiating a get_URL request to trustpilot
3- Using beautiful soup library, scraped html is parsed to read the text.
4- Using textblob, polarity and subjectivity of the text is determined
5- Using If Else statement, sentiment is determined i.e if polarity is greater than zero, sentiment is positive, else it is negative. A zero polarity means neutral sentiment.
