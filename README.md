 Table of content:
 =================
• introduction

       • Ticket Tagger with Feature Selection using PSO Algorithm
         
       • Explain for some terminologies

• Requirements 

• Datasate

       • Pre-processing 

• Project files

• Resource links

• References


# Introduction
## Ticket Tagger with Feature Selection using PSO Algorithm 

Ticket tagger is subject project for four students that aimed to classify Github issues into three categories (bug, question, and enhancement) in order to help the users to manage thier time and priority.  we used fastText pretrained model to generate  the text vectors (300 vec) then we used particle swarm optimization algorithm (PSO) for feature selection. finally, we trained selected feature using SVM model.

## Terminologies
Explain for some of terminologies:

* particle swarm optimization (PSO) algorithm [1] :  is a metaheuristic algorithm based on the concept of swarm intelligence capable of solving complex mathematics problems existing in engineering

*  fastText [2] : fastText is a library for efficient learning of word representations and sentence classification. We use it to represent every feature as a vector.

*  Word2Vec [3] :is a technique  that creates word embeddings in the field of Natural Language Processing (NLP). It takes in words from a large corpus of texts as input and learns to give out their vector representation


# Requirements: 

* install pyswarms library. 
* install fasttext pre-trained model for english language. 
* install W2V  pre-trained model. 

# Dataset 

The preprocessing on data has been done in two files:

*  A- Data cleaning by removing emojis, symbols, pictographs, non-English charecters, numbers ,and links.
*  B- Data cleaning in A ,word stemming, and stop words removal. 

(A) maintained an acceptable accuracy, while (B) decreases the accuracy. so, word stemming and stop words removal wasn't considered in our work.


# Project files 

This repository contains project files as following : 

*  dataset folder.
*  fasttext folder (contains fasttext pretrained model )
*  w2v folder (contains W2V pretrained model as try )
*  others files contains source code in Python & some documents.
*  Datasets, dataset after cleaning and the main dataset (will be shared with you later due to its large size).
*  Dataset cleaning method in python. 

# Resouce Links

* you can install fastText from this link : https://fasttext.cc/docs/en/pretrained-vectors.html

* you can install W2V from this link: https://newbedev.com/import-googlenews-vectors-negative300-bin

# References 

 * [1]- https://www.intechopen.com/chapters/69586
 * [2]- https://towardsdatascience.com/fasttext-ea9009dba0e8
 * [3]-  https://www.section.io/engineering-education/what-is-word2vec/

