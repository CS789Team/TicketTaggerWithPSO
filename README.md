# Table of content:
• introduction

       • Ticket Tagger with Feature Selection using PSO Algorithm
         
       • Explain for some terminologies

• Requirements 

• project files



# Ticket Tagger with Feature Selection using PSO Algorithm 

Ticket tagger is subject project for four students that aimed to classify Github issues into three categories (bug, question, and enhancement) in order to help the users to manage thier time and priority.  we used fastText pretrained model to generate  the text vectors (300 vec) then we used particle swarm optimization algorithm (PSO) for feature selection. finally, we trained selected feature using SVM model.

This repository contains project files as following : 

*  dataset folder.
*  fasttext folder (contains fasttext pretrained model )
*  w2v folder (contains W2V pretrained model as try )
*  others files contains source code in Python & some documents.

Run requirements: 

* install pyswarms library. 
* install fasttext pre-trained model for english language. you can install it from this link : https://fasttext.cc/docs/en/pretrained-vectors.html
* install W2V  pre-trained model. you can install it from this link:
https://newbedev.com/import-googlenews-vectors-negative300-bin

Explain for some of terminologies:

fastText : fastText is a library for efficient learning of word representations and sentence classification. we use it to represent every feature as a vector.


The preprocessing on data has been done in two files:

A- Data cleaning by removing emojis, symbols, pictographs, non-English charecters, numbers ,and links.
B- Data cleaning in A ,word stemming, and stop words removal. 
