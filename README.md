# Page-Ranking of Web graph
The PageRank algorithm is implemented with and without random teleportations using the
following two methods – </br>
A. Finding the principal left eigenvector of the probability transition matrix directly i.e., by making use
of numerical linear algebra packages </br>
B. Finding the principal left eigenvector of the probability transition matrix Power Iteration method. </br>
Random Teleportations Hyper parameter: Teleportation to
a random page with probability of 0.1

## Running the code

The code can be either run as ipynb file from Jupyter Notebook / as .py file from terminal </br>

Input : </br>
N: Number of nodes </br>
E: Number of edges </br>
Edge list (E edges each between a pair of nodes)

Steps to run: </br>
1. After giving the input, call the function prob_transition_matrix(adj_matrix,alpha) which takes adjacency matrix and teleportation parameter (alpha) as input
2.  
a) Set alpha = 0 to run the algorithm without random teleportation</br> 
b) Set alpha > 0 to run the algorithm with random teleportation
3. Run the algorithm with both methods : numerical linear algebra and power iteration method

## Running Time Analysis


