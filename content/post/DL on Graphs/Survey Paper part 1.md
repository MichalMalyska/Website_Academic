---
title: Writeup on Deep Learning on Graphs A Survey by Zhang et al.
date: 2019-07-12
math: true
diagram: true
draft: true
---

# Preliminaries



This is the first part of an overview of Machine Learning methods on Graphs.


In this post for Machine Learning on graphs:
- [x] Introduction to Graph Methods
- [x] Graph Neural Networks (GNN's)
- [x] Graph Convolutional Networks (GCN's)
- [ ] Attention on Graphs
- [ ] Graph Autoencoders
- [ ] Graph VAE's
- [ ] Graph RNN's
- [ ] Graph RL

# Introduction to Graph Methods

TODO: Why ML on graphs is important.

## Notation:

Let:

`$G  = (V, E) $` - The Graph as a set of Vertices (Nodes) and Edges

`$N, M$` - The number of nodes and edges respectively

`$\mathbb{F}^V , \mathbb{F}^E$` - The Features of Nodes and Edges respectively

`$A$` - the Adjacency matrix

`$D(i,j) = \sum_{j \neq i} A(i,j)$` - Diagonal Degree matrix

`$L = D - A$` - The Laplacian matrix

`$Q \Lambda Q^T = L$` - The eigendecomposition of the Laplacian

`$P = D^{-1}A $` - The Transition Matrix

`$ $`
