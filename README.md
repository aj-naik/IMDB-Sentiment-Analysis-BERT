# IMDB-Sentiment-Analysis-BERT
Sentiment Analysis for IMDB Movie dataset using BERT, a Transformer model created by Google. BERT model used here is Hugging Face's implementation of BERT.

Did this project to learn more and actually implement BERT for text classification task. Comparing with other NLP algorithms like SVM, logistic regression and other probablistic NLP methods, BERT gave an accuracy of 99%.

Used base-uncased model of BERT and fine tuned it on Stanford's IMDB Movie Dataset. Fine tuned the model with Adam optimizer, SparseCategoricalCrossentropy loss and SparseCategoricalAccuracy accuracy metric. 

Learning rate was set to 3e-5. Training took around 20 mins per epoch. Increasing learning rate may help converge faster resulting in less time for training per epoch.

Another Implementation of same task would be Official TensorFlow guide found here:
https://www.tensorflow.org/text/tutorials/classify_text_with_bert

I found this implementation a bit messy and complex. So tried doing the same task using Hugging Face transformer library. However one benefit of the official guide is that it gives information on serving the model on Tensorflow Serving which is quite a handy and easy tool to use.
