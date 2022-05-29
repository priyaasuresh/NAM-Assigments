## Comparative Analysis of Traditional Methods and Graph Machine

To compare traditional, similarity-based methods with GraphML algorithms like GCN,
GraphSAGE and GAT for link prediction.

## Problem Statement
The dataset represents corresponding season 7 from the TV Show, Game of Thrones, where each dataset
consists of two CSV files - nodes.csv and edges.csv <br> 
The former provides the list of characters whereas the latter provides the interactions between them.

## Tasks performed
1. Load the dataset from the CSVs into NetworkX to create an undirected graph.
2. Perform EDA on the dataset (Check for isolates, self-loops, etc)

3. Calculate the following measures:
   - Betweenness
   - PageRank
   - Local clustering coefficient

4. Find communities using Spectral Clustering
5. Link Prediction using Traditional Methods
6. Link Prediction using GraphML
7. Perform a comparison between traditional and GraphML
