# FGE_algorithm
========================================================================
    FGE_algorithm
========================================================================

FGE is an algorithmic framework for representational learning on graphs. Given any graph, it can learn continuous feature representations for the nodes, which can then be used for various downstream machine learning tasks. 

The code works under Windows , Linux and other Unix variants with python. 

/////////////////////////////////////////////////////////////////////////////

Parameters:
Input graph path (-input:)
Output graph path (--output_n2v:)
Number of dimensions. Default is 128 (--dimensions:)
Length of walk per source. Default is 10 (--walk-length:)
Number of walks per source. Default is 2048 (--num-walks:)
Context size for optimization. Default is 10 (--window-size:)
Number of epochs in SGD. Default is 1 (-iter:)
Return hyperparameter. Default is 1 (--p:)
Inout hyperparameter. Default is 1 (--q:)
Graph is directed. (--directed)
Graph is weighted. (--weighted )

/////////////////////////////////////////////////////////////////////////////

Usage:
python ./main_appro_nd.py --input ./karate.edgelist --output_n2v ./karate_embedding --dimensions 128 
