# Quora-Insincere-Questions-Classification
https://www.kaggle.com/c/quora-insincere-questions-classification

Detect toxic content to improve online conversations

An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle this problem head-on to keep their platform a place where users can feel safe sharing their knowledge with the world.

Quora is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions -- those founded upon false premises, or that intend to make a statement rather than look for helpful answers.

In this competition, Kagglers will develop models that identify and flag insincere questions.

File descriptions:

train.csv - the training set

test.csv - the test set

sample_submission.csv - A sample submission in the correct format

Data fields:
qid - unique question identifier
question_text - Quora question text
target - a question labeled "insincere" has a value of 1, otherwise 0

Embeddings:

GoogleNews-vectors-negative300 - https://code.google.com/archive/p/word2vec/

glove.840B.300d - https://nlp.stanford.edu/projects/glove/

paragram_300_sl999 - https://cogcomp.org/page/resource_view/106

wiki-news-300d-1M - https://fasttext.cc/docs/en/english-vectors.html
