# Project Summary

**Author:** Yunxiao Shi

**Project name:** GNN Foundation and Models

**Project goal:** Being command of the basic knolwedge of GNN and learn about some common models.

## Objectives

- [x]  Basics in Graph
- [x]  DeepWalk
- [x]  LINE
- [x]  Node2vec
- [x]  Struc2vec
- [x]  SDNE
- [ ]  GCN
- [ ]  GraphSAGE
- [ ]  PyG
- [ ]  HAN
- [ ]  GTN
- [ ]  Metapath2vec
- [ ]  GATNE
- [ ]  BiNE
- [ ]  SGCN
- [ ]  SiGAT
- [ ]  SDGNN
- [ ]  DySAT
- [ ]  Evolve
- [ ]  DGNN
- [ ]  TGAT
- [ ]  HGNN
- [ ]  DHGNN

## Details

| Task | Content |  Schedule |Evaluation |
|------|--------|---------|-------|
|Basics in Graph|度中心性，特征向量中心性，中介中心性，连接中心性。Pagerank, HITS | | |
|DeepWalk|Randomly walk to generate sequence and regard it as sentence, using ship-gram to get node embedding. | |Applying it to RS has improvement. |
|LINE |Extract structure info and neighbor info, corresponding to Second order and First order similarity seperately. Using KL diversion to calculate the distance of two distributions and the objection function is to minimize it. Concate this two embedding to represent a node.| | Applicable to large-scale Graph  |
|Node2vec |Find nodel's Homophily, or Structural Equivalence. Randomly walk as DFS and BFS strategy by controling probability.| | Better performance than DeepWalk|
|Struc2vec| To find nodes with similiar structure in Graph (They are not connected with each other). Define many formula to calculate structural similarity.| | Good performance to capture node's feature in structure or connection. (Socialist, traffic hub)|
|SDNE| Structural node Embedding based on DL. Applying Encoder and Decoder to one row of Adjacency Matrix to get structural embedding(Second order similarity). And define the First order similarity is the L2 distance between two connected node. The object function is L1 + L2.| |Deep nolinear model, suitable to large graph. Performance is unknow.
|Conclusion|<img width="1231" alt="image" src="https://user-images.githubusercontent.com/63179313/168983669-40888d5b-0079-4b78-ac80-090d147c2b3c.png">|||
||||

