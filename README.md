# Sexism Detection

> This is just the copied over README and files from the original SemEval task. But the README links to their original sources, so I kept it. We can modify later. 


This is the public repository for SemEval 2023 - Task 10. The [overview paper](https://arxiv.org/abs/2303.04222) summarises the dataset, task and participant systems.

The task contains three hierarchical subtasks:

* TASK A - Binary Sexism Detection: a two-class (or binary) classification where systems have to predict whether a post is sexist or not sexist.
* TASK B - Category of Sexism: for posts which are sexist, a four-class classification where systems have to predict one of four categories: (1) threats, (2)  derogation, (3) animosity, (4) prejudiced discussion. 
* TASK C - Fine-grained Vector of Sexism: for posts which are sexist, an 11-class classification where systems have to predict one of 11 fine-grained vectors.

If you use the dataset or accompanying materials, please cite: 

```
@inproceedings{kirkSemEval2023,
title = {{SemEval}-2023 {Task} 10: {Explainable} {Detection} of {Online} {Sexism}},
url = {http://arxiv.org/abs/2303.04222},
doi = {10.48550/arXiv.2303.04222},
author = {Kirk, Hannah Rose and Yin, Wenjie and Vidgen, Bertie and Röttger, Paul},
booktitle = {Proceedings of the 17th {{International Workshop}} on {{Semantic Evaluation}} ({{SemEval-2023}})},
publisher = {{Association for Computational Linguistics}},
year = {2023}
}
```


![Our Taxonomy](https://github.com/rewire-online/edos/blob/main/edos_vectors.png?raw=true)
