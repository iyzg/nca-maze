# Notebook

### 05.07.23

- Perhaps something to try with the maze is that after 1000 steps, you make the alpha of all non-shortest paths to be 0 to incentivize it to kill
    - Might also want to algorithmically bring it in from the edges to slowly kill
- Growing from corners seems a lot more unstable than growing from edges
- Perhaps you have something where you punish "larger" solutions like recent paper that had penalty associated with size and connection length
    - Clune et al. and connection costs is also related to this
    - Modularity, connection cost within zotero to find
- What if instead of growing, it was something like the MNIST where each cell has to classify if it is part of the solution or not?
- Need to modify implementation so that only alive cells perform computation
    - Alive needs to be classified beforehand as valid spaces in the maze
- Pruning backwards from filling a maze to the most efficient path
