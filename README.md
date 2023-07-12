# ForestPrune

Code repository for ForestPrune: Compact Depth-Controlled Tree Ensembles. A Python implementation of ForestPrune can be found in the code directory.

ForestPrune is an optimization framework to post-process tree ensembles by pruning depth layers from individual trees.  Since the number of nodes in a decision tree increases exponentially with tree depth, pruning deep trees drastically compactifies ensembles. The framework is computationally efficient, ensembles with 100s of trees fit on datasets with 10000s of rows can be pruned in seconds, and out-performs many existing ensemble pruning algorithms.

To cite ForestPrune please use:

```
@inproceedings{liu2023forestprune,
  title={ForestPrune: Compact depth-pruned tree ensembles},
  author={Liu, Brian and Mazumder, Rahul},
  booktitle={International Conference on Artificial Intelligence and Statistics},
  pages={9417--9428},
  year={2023},
  organization={PMLR}
}
```
