# MPIQuerier
Uses a computer cluster to answer questions about four bags of words from different sources: enron email messages. Neural Information Processing Systems (NIPS) conference papers, the Daily Kos blog, and the New York Times news articles.
It distributes the data sets across the cluster and each node will read the section of the data it has been assigned. It then presents the user with an interface to enter queries on the data set, the queries are sent to the baby nodes, and finally the head node will compose the results from the baby nodes into an answer presented to the user.
