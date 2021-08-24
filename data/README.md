# Datasets

Los archivos que se encuentran en esta carpeta, son los conjuntos de datos que
se utilizarán durante la implementación de la red neuronal en Pythorch. 
Los enlaces de los archivos son los siguientes:

* [Kaggle Dataset](https://www.kaggle.com/c/fake-news/data)
* [ISOT Fake News Dataset](https://www.uvic.ca/engineering/ece/isot/datasets/fake-news/index.php)

--------------------

## ISOT Fake News Dataset (description)

The ISOT Fake News dataset is a compilation of several thousands fake news and truthful articles, obtained from different legitimate news sites and sites flagged as unreliable b
[Politifact.com](https://polifact.com).

## Fake News: Build a system to identify unreliable news articles

train.csv: A full training dataset with the following attributes:

id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable
1: unreliable
0: reliable

test.csv: A testing training dataset with all the same attributes at train.csv without the label.
submit.csv: A sample submission that you can