# automatic-keyphrase-extraction

This repository contains the algorithm and preprocessed dataset used in the Master Thesis "Applying Deep Learning techniques to terminology extraction in specific domains".

* The **ake_algorithm.py** file contains the Python code of the model developed in this project. The neural network is built on PyTorch and, more specifically, using the Flair library for natural language processing.
* The **INSPEC** folder contains three plain text files, **train.txt**, **dev.txt** and **test.txt**, corresponding to the training set, the evaluation set and the testing set respectively. 

As an example, the following line can be run in a Python IDE (e.g. PyCharm) to execute the BiLSTM-CRF model with two BiLSTM layers using the BERT contextual embedding and 100 epochs:

`-- python ake_algorithm.py --num_epochs 100 --embedding Bert --rnn_layers 2`
