# sentiment-analysis-digikala

The Dataset is all about comments in the Digikala website site. These comments are scraped from Digikala.com and have been labeled based on the stars people who had bought the products gave to them. Also many of the comments are noisy and do not provide a clean data for us and it is not such a reliable source by adding the second label to the data we can ensure a higher accuracy of our training data. For more clarifying the labels:
1 indicates suggesting others to buy 2 means otherwise 3 illustrate a neutral opinion about the product 4 means the person has rate the product, but not suggest whether to buy or not
Finally the two or three digits number indicates the satisfaction percentage of the consumer with the preceding comment.
I have used LSTM for prediction of whether people would like or dislike a product based on the previous comments in the Digikala site
