# TicketTaggerWithPSO

Ticket tagger uses fast Text tool by facebook, the dataset has 30K issues been classified eventually in 3 categories (bug, question, and enhancement). fast Text takes the dataset in the training stage to create a model, . After that it classifies new posts within the 3 categories.

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
