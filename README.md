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
@inproceedings{Skandalis-Moot-Robillard:CORIA-TALN:2023,
    author = "Skandalis, Maximos and Moot, Richard and Robillard, Simon",
    title = "DACCORD : un jeu de donn\'ees pour la D\'etection Automatique d'\'enonC\'es COntRaDictoires en fran\c{c}ais",
    booktitle = "Actes de CORIA-TALN 2023. Actes de la 30e Conf\'erence sur le Traitement Automatique des Langues Naturelles (TALN), \\ volume 1 : travaux de recherche originaux -- articles longs",
    month = "6",
    year = "2023",
    address = "Paris, France",
    publisher = "Association pour le Traitement Automatique des Langues",
    pages = "285-297",
    note = "",
    abstract = "La t\^ache de d\'etection automatique de contradictions logiques entre \'enonc\'es en TALN est une t\^ache de classification binaire, o\`u chaque paire de phrases re\c{c}oit une \'etiquette selon que les deux phrases se contredisent ou non. Elle peut \^etre utilis\'ee afin de lutter contre la d\'esinformation. Dans cet article, nous pr\'esentons DACCORD, un jeu de donn\'ees d\'edi\'e \`a la t\^ache de d\'etection automatique de contradictions entre phrases en fran\c{c}ais. Le jeu de donn\'ees \'elabor\'e est actuellement compos\'e de 1034 paires de phrases. Il couvre les th\'ematiques de l'invasion de la Russie en Ukraine en 2022, de la pand\'emie de Covid-19 et de la crise climatique. Pour mettre en avant les possibilit\'es de notre jeu de donn\'ees, nous \'evaluons les performances de certains mod\`eles de transformeurs sur lui. Nous constatons qu'il constitue pour eux un d\'efi plus \'elev\'e que les jeux de donn\'ees existants pour le fran\c{c}ais, qui sont d\'ej\`a peu nombreux. \textasciitilde\ In NLP, the automatic detection of logical contradictions between statements is a binary classification task, in which a pair of sentences receives a label according to whether or not the two sentences contradict each other. This task has many potential applications, including combating disinformation. In this article, we present DACCORD, a new dataset dedicated to the task of automatically detecting contradictions between sentences in French. The dataset is currently composed of 1034 sentence pairs. It covers the themes of Russia's invasion of Ukraine in 2022, the Covid-19 pandemic, and the climate crisis. To highlight the possibilities of our dataset, we evaluate the performance of some recent Transformer models on it. We conclude that our dataset is considerably more challenging than the few existing datasets for French.",
    keywords = "D\'etection automatique de contradictions, Jeu de donn\'ees, Construction de corpus, T\^ache de paire de phrases, Classification binaire, Analyse s\'emantique de phrases, Fran\c{c}ais",
    url = "http://talnarchives.atala.org/CORIA-TALN/CORIA-TALN-2023/459882.pdf"
}
````
