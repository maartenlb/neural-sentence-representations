This project investigates the effectiveness of different neural models in sentence representation for sentiment analysis. Specifically, we explore how factors such as word order, tree structures, sentence length, subtree supervision, and lemmatization impact classification performance. We implement and evaluate two broad categories of models: Bag-of-Words (BOW) approaches, including neural BOW, Continuous BOW (CBOW), and Deep CBOW, as well as Long Short-Term Memory (LSTM) models, including a standard LSTM and a Tree-LSTM. Our experiments on the Stanford Sentiment Treebank (SST) dataset reveal that accounting for word order improves performance, while the inclusion of tree structures also yields slight benefits. However, supervising sentiment labels at each subtree leads to overfitting without significant performance gains. Sentence length affects models differently, with longer sentences generally posing challenges. Finally, lemmatization does not produce a substantial impact on classification accuracy. These findings provide insights into the relative importance of various linguistic features in neural sentiment classification and contribute to the ongoing development of more effective sentence representation techniques.

Please see the [notebook](https://github.com/maartenlb/neural-sentence-representations/blob/main/neural_sentence_representations_code.ipynb) or read the [paper](https://github.com/maartenlb/neural-sentence-representations/blob/main/neural_sentence_representations_paper.pdf) for the full story. :)
