# sentiment-analysis-digikala-comments

The Dataset used here are comments in the Digikala website illustrating the level of customer satisfaction. These comments were scraped from Digikala.com and have been labeled based on the stars people who had bought the products given to them. Also, many of the comments are noisy and do not provide great insight into the customer's interest level. This data contains three columns. The first column is actually the text of the comment itself. The other two columns are scores and also labels assigned to comments. Choosing which label to act as the target is up to the users, but I have used a modified version of the third column. The other column is the percentage of consumer satisfaction and therefore needs a little bit of processing to find the threshold below which consumers were dissatisfied. 
I have used LSTM to predict whether people would like or dislike a product based on the text of the comments. For better results, Fasttext embedding was used as a pre-trained embedding vector. 
