# Intro to Graph Representation Learning

Hi! You’re probably here because of some talk or lecture I did on graph representation learning. A download link to the slides will also appear here after the talk.

## Further readings and resources

- Graph Representation Learning Book (the ultimate resource)
	- https://www.cs.mcgill.ca/~wlh/grl_book/
- Graph Networks and the importance of relational inductive biases
	- https://arxiv.org/pdf/1806.01261.pdf
- Proof of universality of deepsets:
	- Overview blog post: https://fabianfuchsml.github.io/permutationinvariance/
	- Deep Sets paper (with discrete version of proof): https://arxiv.org/abs/1703.06114
	- Continuous version of proof: https://arxiv.org/pdf/1901.09006.pdf
- Are GNNs universal? Can GNNs express any function on graphs?
	- Short answer: It depends
	- Essentially, since graph isomorphism is in NP, determining graph structure up to isomorphism is already very hard.
	- There's a very good approximate algorithm to solve the graph isomorphism problem called the "Weisfeiler-Lehman isomorphism test"
	- We can compare our existing architectures to see whether they can simulate this test
	- Paper that talks about it: https://arxiv.org/pdf/1810.00826.pdf
- GCN paper
	- https://arxiv.org/abs/1609.02907
- GAT
	- https://arxiv.org/abs/1710.10903
- GATv2
	- https://arxiv.org/abs/2105.14491
- TensorFlow: Intro to Graph Neural Networks talk
	- https://www.youtube.com/watch?v=8owQBFAHw7E
