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


## Assignment 2 Data Stream Algorithms

Learning Objectives: The goal of this assignment is to investigate heavy hitters algorithms
on a real-world dataset, which we have learnt during weeks 4-5.
General Instruction:
This core component in this assignment is to find frequent items on a data stream by
investigating data stream algorithms, including Brute Force approach, Misra-Gries Summary,
and Count Sketch algorithm. Please write a python program to complete the following
components:
- Part I: Brute Force Approach and Performance Evaluation
- Part II: Miisra-Gries Approach and Performance Evaluation
- Part III: Count Sketch Approach and Performance Evaluation

Datasets:
Let’s consider the Spotify playlists dataset, consisting of over 281,000 tracks. After loading the
data (.json file), you will see that each playlist is detailed with: <name,num_holdouts,...,
tracks,num_samples>, where tracks hold the details of each track/song in the playlist.
You can find the data stream files, challenge.json on Canvas.
...


## Assignment problem 
1 Assignment problem (100 pts)
This assignment aims at exploring the PageRank algorithm on big real-world network data.
By working on this assignment, you will learn how to implement the PageRank algorithms
that we have learned in the class. Download the dataset1 'Google-web.txt' from the assign-
ment page on Canvas. Each line of the le represents a directed edge from a source node
to a destination node. Nodes are represented by IDs ranging from 0 to 875712.
The assignment has the following tasks:
....


若您有关于此作业的任何需求，[本人主页](https://github.com/Huluwa-kong), 可添加vx：codingtutor 或者qq：122929048

