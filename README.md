# COMPSCI753
COMPSCI753 Assignments and Projects


## Assignment 1 Locality-sensitive Hashing
Learning Objectives: The goal of this assignment is to investigate Locality-sensitive
Hashing (LSH) framework for near neighbor search on real-world datasets. We have learned
how to construct hash tables using multiple hash functions in LSH family for near neighbor
retrieval in sublinear time. By accomplishing this assignment, you will be familiar with the
following concepts:
● Hash Table Construction
● Hash Table Lookup
● Search Quality Evaluation
General Instruction:
This core component in this assignment is to construct a document retrieval system upon the
LSH framework. This assignment consists of three parts. Please write a python program to
complete the following components:
● Part I: Construct LSH Hash Tables for All News Articles
● Part II: Perform Nearest Neighbor Search for Query Dataset
● Part III: Investigate the Impact of the hash size (k). Plots the Search Quality in F1-score.

Datasets:
Let’s consider two classes of BBC news articles: tech news and entertainment news. In
bitvector_all.csv and bitvector_query.csv, each news article is a tab-separated
line with three columns: <news_id\tword_features\tnews class>, where news_id is a
unique string ID, word_features is a sequence of tab-separated binary values. Each entry in
the word_features refers to the occurrence of a token. You can find their original new articles
in text_all.csv and text_query.csv, accordingly in bbc.zip on Canvas.
Submission:
Please submit a single report (.pdf) and the source code with detailed comments.(.py
or .ipynb or .html) .

Part I: Construct LSH Hash Tables for All News Articles [40 pts]
Part II: Nearest Neighbor Search [35 pts]
Part III: Search Quality Evaluation [25 pts]

若您有关于此作业的任何需求，[本人主页](https://github.com/Huluwa-kong), 可添加vx：codingtutor 或者qq：122929048

