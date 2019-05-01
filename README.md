
# Tutorial for Topological Data Analysis with the Gudhi Library

Topological Data Analysis (TDA) is a recent and fast growing  field providing a set of new topological and geometric tools to infer relevant features for possibly complex data. Here we propose a set of notebooks for the practice of TDA with the python Gudhi library together with popular machine learning and data sciences libraries.


See for instance [this paper](https://arxiv.org/abs/1710.04019) for an introduction TDA for data sciences

### 0 - Install Python Gudhi Library  

See the [installation page](http://gudhi.gforge.inria.fr/python/latest/installation.html) or [conda install](https://anaconda.org/conda-forge/gudhi)

### 1 - Simplex trees and simpicial complexes

Simplicial complexes can be seen as higher dimensional generalization of graphs. They are mathematical objects that are both topological and combinatorial, a property making them particularly useful for TDA.

In Gudhi, (filtered) simplicial complexes are encoded through a data structure called simplex tree. This [notebook](./Tuto-GUDHI-simplex-Trees.ipynb) illustrates the use of simplex tree to represent simplicial complexes.



2 - Persitence homology and metrics


3 - alternative representation of persistence and linearization


4 - Statistical tools for persistence


5 - Machine learning and Deep learning for persistence


6- Alternative filtration and robust TDA


7- Topological Data Analysis and Time series


8- Mapper Algorithm


9- TDA and dimension reduction
