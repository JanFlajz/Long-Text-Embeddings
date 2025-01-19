# MVI SP
author: flajzjan@cvut.cz
# Understanding of long texts
The aim of this semestral work is to research several existing libraries for generating long text embeddings.
The libraries are then compared using availible benchmark datasets. 
Then the examined libraries are used in text classification task to simulate their usability in practice.

# Summary of work
We selected 3 libraries for performing benchmarks based on bitext retrieval using 6 different languages:
- LaBSE
- mUSE
- XLM-Base

We performed this benchmark on two existing dataset:
- Tatoeba which we adjusted for our needs
- BUCC which we used as it is

In this benchmarks the performance of LaBSE and mUSE were slightly better than XLM. 
So we used them for classifing the sentiment of texts from Massive Multilingual Sentiment Corpora which we reduced four our needs.

Finally, we performed a classification using those two libraries and a simple neural network using which LaBSE slightly outperformed mUSE.





