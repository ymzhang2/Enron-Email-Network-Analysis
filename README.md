# Enron-Email-Network-Analysis-

CS6907-13 Big Data and Analytics
Class project #1
R and Graph Analytics

###1. Data Set: Enron Mail Subset 
#####a. Extract the following fields: From, To, Date, Subject, MessageID

Of the 26 people listed, there are connections among many of them. But, you need to find these by processing the email in their folders.

So, writing a function to open maildir, and iterate over people. It will call a function to iterate over their subfolders. Each contains a file “1” which is a mail message. Extract the relevant data and store it someplace.

###2. Graph Analytics: once you have extracted data from the text messages, and assembled it in one or more data structures, you will need to build graph representation. You should do this as a matrix. You should have at least 20 people in your graph; more would be nice.

###3. Deliverables: You will deliver, by putting a zipfile in your group’s Blackboard file, with the following naming convention: Group-N-Project-1.zip, where N is your group number. Your deliverable should encompass the following items:

•	A listing of all R functions that you have written
•	A document listing the people in your graph, the number of edges – indegree and outdegree – for each person
•	The matrix of the graph in a word document
•	Computation of the following metrics:
o	The central persons in your graph (there may be more than one)
o	The betweenness metric for all persons in your graph
o	The prestige 
