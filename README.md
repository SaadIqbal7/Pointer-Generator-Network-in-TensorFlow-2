# Pointer Generator Network in TensorFlow 2

This repository contains Jupyter Notebook for implementing Machinne Translation from English To Python code. The network I used was Pointer Generator Network. You can check out the PGen Network in the paper [Get To The Point: Summarization with Pointer-Generator Networks](https://arxiv.org/abs/1704.04368).

Note: The Notebook in this repository does not implement the Coverage mechanism (mentioned in the paper) currently.

Beside the notebook, the repository contains a dataset file, a file containing python vocabulary and two helper classes for generating vocabulary and generating examples compatible with the network.

The dataset file, Dataset.xlsx, contains english sentences and their equivalent code in python. All the sentences were written so currently the dataset is small in size and does not cover all the python operators.

The python vocabulary file, Python Vocabulary.xlsx, contains the python vocabulary (operators and keywords).

The network can be trained with pre trained glove word embeddings, or the word embeddings can be trained from start. You can download the pre trained word embeddings from [this link](https://nlp.stanford.edu/projects/glove/). The notebook contains a helper function for loading glove word embeddings of any dimension.
