# DACCORD dataset

This repository contains the files for the dataset DACCORD, a dataset for automatic detection of contradictions between sentences in French.

It is also available on [huggingface.co](https://huggingface.co/datasets/maximoss/daccord-contradictions).

# How to use in python

```
import pandas as pd

dataset = pd.read_csv("./daccord_dataset.tsv", sep='\t')
print(dataset)
```

# Cite

**BibTex**
````BibTeX
@inproceedings{skandalis-etal-2024-new-datasets,
    title = "New Datasets for Automatic Detection of Textual Entailment and of Contradictions between Sentences in {F}rench",
    author = "Skandalis, Maximos  and
      Moot, Richard  and
      Retor{\'e}, Christian  and
      Robillard, Simon",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.1065",
    pages = "12173--12186",
    abstract = "This paper introduces DACCORD, an original dataset in French for automatic detection of contradictions between sentences. It also presents new, manually translated versions of two datasets, namely the well known dataset RTE3 and the recent dataset GQNLI, from English to French, for the task of natural language inference / recognising textual entailment, which is a sentence-pair classification task. These datasets help increase the admittedly limited number of datasets in French available for these tasks. DACCORD consists of 1034 pairs of sentences and is the first dataset exclusively dedicated to this task and covering among others the topic of the Russian invasion in Ukraine. RTE3-FR contains 800 examples for each of its validation and test subsets, while GQNLI-FR is composed of 300 pairs of sentences and focuses specifically on the use of generalised quantifiers. Our experiments on these datasets show that they are more challenging than the two already existing datasets for the mainstream NLI task in French (XNLI, FraCaS). For languages other than English, most deep learning models for NLI tasks currently have only XNLI available as a training set. Additional datasets, such as ours for French, could permit different training and evaluation strategies, producing more robust results and reducing the inevitable biases present in any single dataset.",
}

@inproceedings{skandalis-etal-2023-daccord,
    title = "{DACCORD} : un jeu de donn{\'e}es pour la D{\'e}tection Automatique d{'}{\'e}non{C}{\'e}s {CO}nt{R}a{D}ictoires en fran{\c{c}}ais",
    author = "Skandalis, Maximos  and
      Moot, Richard  and
      Robillard, Simon",
    booktitle = "Actes de CORIA-TALN 2023. Actes de la 30e Conf{\'e}rence sur le Traitement Automatique des Langues Naturelles (TALN), volume 1 : travaux de recherche originaux -- articles longs",
    month = "6",
    year = "2023",
    address = "Paris, France",
    publisher = "ATALA",
    url = "https://aclanthology.org/2023.jeptalnrecital-long.22",
    pages = "285--297",
    abstract = "La t{\^a}che de d{\'e}tection automatique de contradictions logiques entre {\'e}nonc{\'e}s en TALN est une t{\^a}che de classification binaire, o{\`u} chaque paire de phrases re{\c{c}}oit une {\'e}tiquette selon que les deux phrases se contredisent ou non. Elle peut {\^e}tre utilis{\'e}e afin de lutter contre la d{\'e}sinformation. Dans cet article, nous pr{\'e}sentons DACCORD, un jeu de donn{\'e}es d{\'e}di{\'e} {\`a} la t{\^a}che de d{\'e}tection automatique de contradictions entre phrases en fran{\c{c}}ais. Le jeu de donn{\'e}es {\'e}labor{\'e} est actuellement compos{\'e} de 1034 paires de phrases. Il couvre les th{\'e}matiques de l{'}invasion de la Russie en Ukraine en 2022, de la pand{\'e}mie de Covid-19 et de la crise climatique. Pour mettre en avant les possibilit{\'e}s de notre jeu de donn{\'e}es, nous {\'e}valuons les performances de certains mod{\`e}les de transformeurs sur lui. Nous constatons qu{'}il constitue pour eux un d{\'e}fi plus {\'e}lev{\'e} que les jeux de donn{\'e}es existants pour le fran{\c{c}}ais, qui sont d{\'e}j{\`a} peu nombreux. In NLP, the automatic detection of logical contradictions between statements is a binary classification task, in which a pair of sentences receives a label according to whether or not the two sentences contradict each other. This task has many potential applications, including combating disinformation. In this article, we present DACCORD, a new dataset dedicated to the task of automatically detecting contradictions between sentences in French. The dataset is currently composed of 1034 sentence pairs. It covers the themes of Russia{'}s invasion of Ukraine in 2022, the Covid-19 pandemic, and the climate crisis. To highlight the possibilities of our dataset, we evaluate the performance of some recent Transformer models on it. We conclude that our dataset is considerably more challenging than the few existing datasets for French.",
    language = "French",
}
````
**ACL**

Maximos Skandalis, Richard Moot, Christian Retoré, and Simon Robillard. 2024. [New Datasets for Automatic Detection of Textual Entailment and of Contradictions between Sentences in French](https://aclanthology.org/2024.lrec-main.1065). In *Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)*, pages 12173–12186, Torino, Italy. ELRA and ICCL.

And

Maximos Skandalis, Richard Moot, and Simon Robillard. 2023. [DACCORD : un jeu de données pour la Détection Automatique d’énonCés COntRaDictoires en français](https://aclanthology.org/2023.jeptalnrecital-long.22). In *Actes de CORIA-TALN 2023. Actes de la 30e Conférence sur le Traitement Automatique des Langues Naturelles (TALN), volume 1 : travaux de recherche originaux -- articles longs*, pages 285–297, Paris, France. ATALA.

# Acknowledgements

This work was supported by the Defence Innovation Agency (AID) of the Directorate General of Armament (DGA) of the French Ministry of Armed Forces, and by the ICO, _Institut Cybersécurité Occitanie_, funded by Région Occitanie, France.
