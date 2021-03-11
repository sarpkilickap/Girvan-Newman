## Girvan-Newman Algorithm

Girvan-Newman algorithm is used to find number of connected components in a network. Communities in a network can be detected with this algorithm. This algorithm removes edges with the highest betweenness until there is no edges remain. Betweenness is the number of shortest paths between pairs of nodes. For further information please visit: https://en.wikipedia.org/wiki/Betweenness_centrality 

### Algortihm is simply explained as:
 
  1. Calculate the betweenness of all edges in a network.
  2. Remove edges with highest betweenness (If a betweenness of two different edges is the same, remove them in random order.).
  3. Recalculate betweenness of all remaining edges since shortest paths is changing when we remove edges.
  4. Repeat step 3 & 4 until no edges remain.

Data is provided by Dr. Islem Rekik, and code is implented for her Graph Theory lecture at ITU in fall of 2020/2021. Her lecture videos are in Basira Lab YouTube channel. Link: https://www.youtube.com/watch?v=dEGmpwPMBH0&list=PLug43ldmRSo3MV-Jgjr30E5SpwNKkjTvJ&ab_channel=BASIRALab 
