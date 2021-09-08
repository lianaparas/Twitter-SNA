# Twitter-SNA
Create reply/mention graph from twitter users interaction under 'Climate Change' topic using NetworkX with PageRank Centrality

**Social Network Analysis**


SNA is a product of social computing and it analyzes social structures using network analysis or what mathematicians call a graph (Bersini, 2005). As in graph theory, the social network is a network of nodes and arcs (Haggett, 1967; James et al., 1970) representing the structures of the relationships among the actors.
 
Most of the studies on SNA are about social relationships (friendship, knowledge, gossip, information), economic relationships (companies’ business relations, consumer behavior, goods and services, brands, finance and banks, stocks, etc.), information and communication technology (ICT) (internet traffic, computer networks, peer-to-peer, the Web), or biological networks (neurons, nervous system, diseases, etc.) (Martin, 2000; Dorogovtsev and Mendes, 2003; Bersini, 2005; Martino and Spoto, 2006; Healey, 2006).




***In this project, I will create a network graph of twitter users based on their interaction (mention and reply).
Dataset was collected using Twitter API under 'Climate Change' topic, started from Oct 2017 to Oct 2018.***


Here are the steps!

1. Extract node and edgelist from dataset
2. Using NetworkX, turn the edgelist to directed graph
3. Separate the largest component from the whole network
4. Count the Pagerank score of each nodes in the largest component
5. Finally, Visualize the final network
