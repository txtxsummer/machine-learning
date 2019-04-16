## Introduction
 - Discover the underlying structure of the data
	 - Unsupervised task, not predicting anything specific
<br/><br/>
 - What sub-populations exist in the data?
	 - How many are there?
	 - What are their sizes?
	 - Do elements in a sub-population have any common properties?
	 - Are sub-populations cohesive? Can they be further split up?
	 - Are they outliers?
## Types of Clustering Methods
- Goal
	- Monothetic: cluster members have some common property
		- E.g. all are males aged 20-35, or all have X% response to test B
	- Polythetic: cluster members are similar to each other
		- Distance between elements defines membership
<br/><br/>
- Overlap
	- Hard clustering: clusters do not overlap
		- Element either belongs to a cluster or not
	- Soft clustering: clusters may overlap
		- “strength of association” between element and cluster
<br/><br/>
- Flat or hierarchical
	- Set of groups vs. taxonomy
## Popular Clustering Methods
- K-D trees
	- Monothetic, hard boundaries, hierarchial
<br/><br/>
- K-means clustering
	- Splits data into specified number if populations
	- Polythetic, hard boundaries, flat
<br/><br/>
- Gaussian mixtures (EM algorithm)
	- Fits a mixture of K Gaussians to the data
	- Polythetic, soft boundaries, flat
<br/><br/>
- Agglomerative clustering
	- Creates an “ontology” of nested sub-populations
	- Polythetic, hard boundaries, hierarchical


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUyNDc5Nzk3MiwtMTMzMjgxNTU3OF19
-->