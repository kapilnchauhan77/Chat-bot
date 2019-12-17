# Chat-bot
This is Chat bot made using Transformer Neural Network Architecture and Reddit Comments dataset

You can train your own model and tokenizer by performing some preprocessing after downloading the dataset from here: https://www.reddit.com/r/datasets/comments/3bxlg7/i_have_every_publicly_available_reddit_comment/

This the result of a 16000 vocab size tokenizer and just a month of data which is very less when trained for just 20 epochs, however, the result was still pretty satisfying but more data and a vocab size of 100,000 would yield far better results.

Also, this data also has subreddit information, so a chatbot with specific genre in mind like sci-fi, comedy or even quantum physics can be made. Note, that training with only data from a specific subreddit will result in more human like chat bot which is expert in the topic of that sub reddit.

If you want to try out the model trained for 20 epochs with 16000 vocab size tokenizer and 1 month data, dowload the weights from here: File Uploading..
