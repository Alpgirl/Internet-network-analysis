# Internet-network-analysis
Network of routers connected to each other compiled by the Center for Applied Internet Data Analysis (CAIDA). Nodes are routers, and they are connected if they are directly connected via cables. 

We consider these the following qiestions:
### Network Structure:

1. *What is the current structure of the network?*
    - Is the network/graph directed or undirected? 
    - How many edges are in the network?
	- Degree, edge distribution
    - Is the graph sparse or dense? Define sparse and why you chose this definition
    - What is the average degree, nth moment, standard deviation in the network? 
	- Does your network have cycles? Self-loops?
	- Weighted or non-weighted?
	- How many isolated components are there?
	- plot/visualize network
	- Graph properties (diameter, raduis, average distance, no of connected components, size of largest cluster, connectivity, clustering coefficient...)
	
	
	
### Network Comparison to other networks(Erdos-Renyi, Scalar Free):

1. *Any similarities/differences between this network and other networks*
    - Critical exponent/phase transition? 
    - What are the possible mechanisms of network formation?
	- use formulas from lecture for comparison e.g Lecture 3 pg 53 (Lecture 3 in general)


	
### Centralities Analysis:
   Centralities are a key concept in network analysis. They provide numerical values that help identify the most important nodes within a network. There are several types of centralities:

   - Degree Centrality: How many direct connections does a node have?
   - Betweenness Centrality: How often does a node appear on the shortest paths between other nodes?
   - Closeness Centrality: How close is a node to all other nodes in the network?
   - Eigenvector Centrality: How connected is a node to other highly connected nodes?
   - Katz Centrality: How influential is a node considering the infinite walk of the network?
   - PageRank Centrality: Considering link direction and weight, how important is a node?
   - Harmonic Centrality: How easily can a node be reached from other nodes?
   - Percolation Centrality: How critical is a node for network connectivity?
   
   These are general definitions of centralities, but what do these centralities mean in our specific netork. E.g. router with highest degree centrality is on the longest.
   Feel free to remove any centrality. Make a table of top 10 of these centralities and analyze what will happen to the network with removal of these nodes (see graph properties and connectivity).


### Community Detection:
   Community detection is about finding clusters or groups of nodes which are more densely connected to each other than to the rest of the network.

   - What are the communities within the network?
   - How densely connected are the nodes within the same community?
   - How many communities are there in the network?
   - What are the characteristics of each community?
   

### Network Connectivity:
   Network connectivity refers to the minimum number of elements that need to be removed for a network to become disconnected.

   - How robust is the network against failures or attacks?
   - What are the weak points in the network?
   - How can the network be made more robust


   
### Path Analysis:
   Path analysis involves finding the paths between nodes in a network.

   - What are the shortest paths between nodes?
   - What are the most used paths?
   - How many unique paths exist between two nodes?
