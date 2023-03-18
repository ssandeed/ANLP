COVID-19 Vaccine Intent Expressions dataset
===========================================

License: Community Data License Agreement - Sharing - Version 1.0
https://cdla.dev/sharing-1-0/

We have used parts of VIRADialogs as-is for the purpose of this dataset.
All credit for VIRADialogs belongs to Johns Hopkins University, they are the sole owners of VIRADialogs.
VIRADialogs is available at vaxchat.org/research.

==========================================

The COVID-19 Vaccine Intent Expressions dataset containts 7,990 variying expressions for common questions about COVID-19 vaccines.

We collaborated with a team at Johns Hopkins University to curate a list 181 such common questions.

We then showed annotators a question from the list and asked them to express it in their words, imagining they are chatting with a knowledgable friend.

A subset of 324 expressions in this dataset are utterances taken from VIRADialogs, a dataset of conversations of users with a chatbot about COVID-19 vaccines.

The data is split to 3 files, train.csv and dev.csv and test.csv.

Each file contains the following columns:

1. sentence - the expression written by an annotator (or taken from VIRADialogs)
2. label - the question for which the expression was written
3. label_idx - the running class index associated with this label

If you use this dataset please cite:

Benchmark Data and Evaluation Framework for Intent Discovery Around COVID-19 Vaccine Hesitancy
Shai Gretz, Assaf Toledo, Roni Friedman, Dan Lahav, Rose Weeks, Naor Bar-Zeev, João Sedoc, Pooja Sangha, Yoav Katz, Noam Slonim
arXiv, 2022