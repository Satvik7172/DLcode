# DLcode
Models used are:-
1-RNN(without pretrained embedding)
2-RNN(with pretrained embedding)
3-CNN(without pretrained embedding)
4-CNN(with pretrained embedding)

Performance of RNN(without pretrained embedding):-
Accuracy-75.74%
Training time-25.35

Performance of RNN(with pretrained embedding):-
Accuracy-79.25%
Training time-34.4740

Performance of CNN(without pretrained embedding):-
Accuracy-78.25%
Training time-24.063

Performance of CNN(with pretrained embedding):-
Accuracy-76.749
Training time-28.458

The best performing model on train-test split is RNN(with pretrained embedding) which i have choosen for final prediction on test data.

Observations:-
1-RNN gives better accuracy when used with pretrained embeddings.
2-CNN performs poor when pretrained embeddings are used as compare to when pretrained embeddings are not used.
3-Without pretrained embeddings CNN performs slightly better than RNN.
4-Highest accuracy is achieved by RNN(with pretrained embeddings) may be due to the reason that RNN's are more suited for text data.

Data Preprocessing Steps:-
1-All punctuations are removed first using python library (re)
2-Common word are removed using pyhton stopwords library.
3-Different form of same words are removed using python WordNetLemmatizer library.

