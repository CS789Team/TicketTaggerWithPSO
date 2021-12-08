# TicketTaggerWithPSO

Ticket tagger is subject project for four students that aimed to classify Github issues into three categories (bug, question, and enhancement) in order to help the users to manage thier time and priority.  we used fastText pretrained model to generate  the text vectors (300 vec) then we used particle swarm optimization algorithm (PSO) for feature selection. finally, we trained selected feature using SVM model.

This repostriy contains project files as following : 

*  dataset folder.
*  fasttext folder (contains fasttext pretrained model )
*  w2v folder (contains W2V pretrained model as try )
*  others files contains source code in Python & some documents.

# Our work:

 - searching for enhancement idea. 
 - discuss with Dr.Wojdan about swarm idea.
 - choosing idea (elimnate uninformative words from issue description) 
 - preparing source code environment.
 - we have tested the tool and found out that the metrics after the 10-FOLD for "question" category is way much lower than what've been presented on the paper. The latest result in our run were :
precision:  0.589
recall:  0.269
f1 score:  0.369

- we're considering each issue (title and description) as the practical in the PSO. our goal is to summarize each issue using PSO (text summarization), in order to reduce the training time and reduce memory usage.
- we are facing issue in certain file and we tried to contact with authors.
- we wrote the requirement and upload it here.
- we  drew the initial sequeces digram on same file of the requirement and add it in the Github
- we tring to build the source code in python language
