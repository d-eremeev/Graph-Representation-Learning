# Materials for <font color=#1F45FC> "Introduction to Graph Representation Learning" </font> mini-course.

### <a href="https://github.com/d-eremeev/">Dmitry Eremeev</a>
<img src="Seminars/pictures/MP.jpg" width=700>

The mini-course covers the basics of **Graph Representation Learning** / **Graph Neural Networks**. 

The following topics are included:
- Motivation for graph representation learning. Several examples of benchmarks.
- Brief review of graph and matrix theory, notion of embeddings.
- Necessary **NLP** models reminder: from **word2vec** to **Transformers**. 
- **Random Walk** Graph Embeddings: **node2vec**, **struct2vec**.
- **Message Passing** Embeddings: **GraphSAGE**, **Graph Attention Network**.
- **Unsupervised** Graph Embeddings, notion of **Triplet Loss**.

Repository is organized as follows:
- <font color=#2B60DE>**Graph_Slides.pdf** </font> - materials for the lectures
- **Seminars**:
    1. <font color=#2B60DE>**PyTorch_Geometric_Dataset.ipynb**</font> - introduces **CORA** dataset, covers the creation of <font color=#EE4C2C>**PyTorch Geometric Dataset**</font> based on this graph. This dataset will be used in the following seminars for model training.
    2. <font color=#2B60DE>**GraphModel_Supervised.ipynb**</font> - acquaints with <font color=#EE4C2C>**NeighborSampler**</font> and the concept of **mini-batch learning** on large graphs. Then the training process of supervised **Graph Attention Network** is covered.
    3. <font color=#2B60DE>**GraphModel_Unsupervised.ipynb**</font> - covers training of unsupervised **GraphSAGE** model. Visualization of resulting node embeddings using **UMAP** is included.
  
<img src="Seminars/pictures/CORA embeddings.png" width=700>
