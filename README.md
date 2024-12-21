# Phylogeny-Inspired Sentence Semantic Clustering

## Project Introduction
  Sentence semantic clustering is a natural language processing task with various potential applications. With the development of large language models and representation learning, one straightforward solution is to embed all sentences in the source dataset into an Euclidean feature space, and then perform clustering algorithms like K-Means and DBScan on it. However, this solution depends heavily on the quality of language models used and is susceptible to occasional failures, because embeddings produced by language models may not always capture the true semantic relationships between sentences, leading to suboptimal clustering results. A better sentence-wise similarity metric should be designed and utilized for the task.
  To this end, we aim to incorporate new terms into the similarity metric, inspired by several algorithms in computational biology. One of the most important is measuring structural similarity by sequence alignment. After that, a phylogeny algorithm, namely Neighbor Joining, could be applied, yielding a tree with leaves as original sentences, which represents the hierarchical semantic clustering. This method could provide a more reliable and explainable alternative to conventional language-model-based techniques, with increased adaptability across different domains and linguistic contexts. 

## How to Use
  The final version of the code is located in the python file [NJ_Parallel_Entropy_Final.ipynb](https://github.com/Y3JUN/CS-466-Project/blob/main/NJ_Parallel_Entropy_Final.ipynb). Change the file path to according files before running. Also, feel free to adjust different linear combinations of the variable `distance_mat_final` to produce different clustering result. For cluster dataset with embeddings, download the dataset [Here](https://drive.google.com/file/d/1gsz7pPKkrcnf2CXTE2Y2H0JzORmdVHL7/view?usp=sharing)


## Group Member: 
- Dongliang Zhang / [dz17@illinois.edu](dz17@illinois.edu)
- Yejun Park / [yejunp2@illinois.edu](yejunp2@illinois.edu])
- Mingyi Lin / [mingyil3@illinois.edu](mingyil3@illinois.edu)



## Acknowledgement
**This repository is exclusively designated for the course project of UIUC CS466 (Fall 2024). All work within this repository is done for academic and exercise purposes only. By grading this project, the faculty fully approves the legality of the repository. The authors assume no warranty or legal responsibility for its use. Except for the course project development and grading, no other use is permitted. This repository may be removed after the semester concludes.**
