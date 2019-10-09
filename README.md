# Bert

This repository is an easy and fast implementation of [BERT](https://arxiv.org/pdf/1810.04805.pdf) for NER.
The BERT pretrained model has been fine tuned using microsoft
implementation of BERT.

BERT is an language model developed by Google which can be fine tuned for
downstream tasks like NER, sentiment analysis, question answering etc.
It is an unsupervised model trained on a large dataset which can be used in a
semi supervised way by training it on a small dataset. It performs extremely well.
It uses a bi-directional LSTM.

To summarize BERT most simply :

It performs 2 tasks:
1. Masking : 15 % of the tokens in the original text are chosed randomly 
which are masked. Now, masking happens in ways.
..* 80 % of the tokens are masken with [MASK].
..* 10% are not masked.
..* 10 % are masked with random tokens.

2. Next sentence prediction : It has a binary predictor wich perdicts whether
the following sentence is indeeed the next sentence.



## Reference : https://github.com/microsoft/nlp
