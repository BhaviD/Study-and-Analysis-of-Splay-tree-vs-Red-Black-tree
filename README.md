# Study & Analysis of Splay tree vs Red Black tree

The splay tree, a self-adjusting form of binary search tree, is developed and analyzed. Much has been said in praise of self-adjusting data structures, particularly Splay Trees. Splay tree is most suited to skewed key-access distributions as it attempts to place the most commonly accessed keys near the root of the tree. Theoretical bounds on worst-case and amortized performance (i.e. performance over a sequence of operations) have been derived which compare well with  those for optimal binary search trees. In this project, we compare the performance of two different techniques of Splay Tree with that of Red Black Tree. Comparisons are made for various tree sizes, levels of key-access-frequency skewness and ratios of insertions and deletions to searches. The results show that, because of the high cost of maintaining self-adjusting trees, in almost all cases the Red Black Tree outperforms Splay Tree in terms of CPU time. Splay tree seem to perform best in a highly dynamic environment, contrary to intuition.

The splay tree, a self-adjusting form of binary search tree, is studied and analyzed. The binary search tree is a data structure for representing tables and lists so that accessing, inserting, and deleting items is easy. On an n-node splay tree, all the standard search tree operations have an amortized time bound of O(log n) per operation, where by “amortized time” is meant the time per operation averaged over a worst-case sequence of operations. Thus splay trees which has two approaches namely, Top down and Bottom up are as efficient as Red Black tree when total running time is the measure of interest. Moreover, Top down approach is a faster than bottom up approach. The efficiency of splay trees comes not from an explicit structural constraint, as with balanced trees, but from applying a simple restructuring heuristic, called splaying, whenever the tree is accessed.
