Derivation and implementation (not my own implementation) of the fornberg algorithm 

What is the fornberg Algorithm?
A finite difference is a method of approximating derivatives. In the case of a uniform mesh (uniform step size), we can simply cancel via adding together the taylor series expansions of the next step and the previous step.
But, when we introduce a non-uniform mesh like chebyshev nodes, we must introduce a means to derive the weights of each calculation

= The fornberg algorithm is the numerically stable and efficient means by which we calculate the weights for a finite difference
