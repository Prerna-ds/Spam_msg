# Spam_msg
What we have here in our data set is a large collection of text data (5,572 rows of data). Most Machine Learning algorithms rely on numerical data to be fed into them as input, and email/sms messages are usually text heavy.

We need a way to represent text data for machine learning algorithm and the bag-of-words model helps us to achieve that task. It is a way of extracting features from the text for use in machine learning algorithms.

In this approach, we use the tokenized words for each observation and find out the frequency of each token.

Using a process which we will go through now, we can convert a collection of documents to a matrix, with each document being a row and each word(token) being the column, and the corresponding (row,column) values being the frequency of occurrence of each word or token in that document.
