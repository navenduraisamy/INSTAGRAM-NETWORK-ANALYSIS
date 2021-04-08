# INSTAGRAM-NETWORK-ANALYSIS

  Taking an instagram account, list of users who follow the account holder and being followed back (best friends) were found. All the followers of the bestfriends' profiles were scrapped through [phantombuster](https://phantombuster.com/) .The directed edges were established between the nodes based on their following  (a-->b, means a follows b). The following analysis was made on the resulting network. 


-  strongly connected components &amp; giant component
-  girvan newman community detection
-  hubs and authorities
-  page rank
-  centrality measures
    - indegree centrality
    - outdegree centrality
    - betweenness centrality
    - closeness centrality

## Datasets
  The dataset `bestfriendsgraph-following.csv` has been used for analysis. It consists of `72 nodes` and `464 edges`. The dataset has only two columns. The first column consist of user and second column consist of accounts being followed by user in first column. 


## Requirements
```
pip install networkx
pip install python-igraph
pip install pandas
pip install matplotlib
pip install tqdm
```
