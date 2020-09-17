# Deep-Learning-Papers
----------------------

Daily analysis of interesting deep learning papers.
- To get into a topic it is better to start of with survey papers and go deep into papers with interesting ideas

## [Efficient Transformers: A Survey](https://arxiv.org/pdf/2009.06732v1.pdf)
-------------------------------------

### Abstract
-------------

Transformer model architectures have garnered immense interest lately due to their effectiveness across a range of domains like language, vision and reinforcement learning. In the
field of natural language processing for example, Transformers have become an indispensable staple in the modern deep learning stack. Recently, a dizzying number of “X-former”
models have been proposed - Reformer, Linformer, Performer, Longformer, to name a few which improve upon the original Transformer architecture, many of which make improvements around computational and memory efficiency. With the aim of helping the avid researcher navigate this flurry, this paper characterizes a large and thoughtful selection of
recent efficiency-flavored “X-former” models, providing an organized and comprehensive overview of existing work and models across multiple domains.

### Interesting Ideas
---------------------

#### Self-Attention mechanism

- modeling pairwise interaction in a model requires a polynomical model of order 2.
- 
- advatage: modeling long sequence applications
- issues: quadratic time and memory complexity

#### Transformer Model

- Multi-layered architectures formed by stacking transformer blocks on top of one another.
- embedding layer converts one-hot encoded input into *d* dimensional embedding


### Analysis
------------

