# Haptik_Challenge
Domain classification of the queries from users

Classification of Haptik user queries into appropriate Classes using NLP and ML techniques.
The goal of the project was to detect the user intent and classify the user chat into the following categories - food,recharge,support,reminders,travel,nearby,movies,casual and other.

A chat can be classified into multiple categories Ex. “Are there any offers going on?” This query could belong to all the domains in which transactions are possible ( travel, recharge, food, movies, home services, etc) Thus it was a Multiclass and multilabel problem.

Implemented a multi-label classifier using the training data. The classifier tagged all the possible domains (food, support etc) for each query using Decision Tree, Logistic Regression and Random forest algorithms.
Achieved a label accuracy of 94% and subset accuracy of 72%
