# phenoClustering

This repository contains the complete results of the experiments presented in the paper:

M. Saletta, A. Bombarda, M. Bellini, L. Goisis, P. Cazzaniga, M. Iascone and D.F. Savo. "*Automated Phenotype-Based Clustering of Clinical Reports Using Large Language Models*". Submitted to International Conference on Artificial Intelligence in Medicine (AIME). 2025.

The files [`textclusters.html`](./textclusters.html) and [`phenoclusters.html`](./phenoclusters.html) are 2-dimensional visualizations (obtained by reducing the dimensionality with t-SNE) of the document vectors obtained from the original text and from the extracted phenotypes, respectively. 

The identified clusters are summarized in the following table:

|ID | From text | From phenotypes |
|---|-----------|-----------------|
|0| Dilated cardiomyopathy | Disorders of the skeletal system |

# Citation

If you find this repository useful for your work, please include the following citation:

```
@inproceedings{phenoClustering,
  author       = {Martina Saletta, Andrea Bombarda, Matteo Bellini, Lucrezia Goisis, Paolo Cazzaniga, Maria Iascone and Domenico Fabio Savo},
  title        = {Automated Phenotype-Based Clustering of Clinical Reports Using Large Language Models},
  booktitle    = {International Conference on Artificial Intelligence in Medicine (AIME) [submitted]},
  year         = {2025}
}
```
