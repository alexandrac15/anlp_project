# anlp_project
Presupposed taxonomies

The project contains the following:

Classifiers.ipynb : various classifiers + experiments
LSTM_pretrained_embeddings_256.ipynb : LSTM model that takes as input pretrained fasttex embeddings. (all experiments have hiddensize set to 256)
LSTM_pretrained_embeddings_128.ipynb : LSTM model that takes as input pretrained fasttex embeddings. (all experiments have hiddensize set to 128)
LSTM_embedding_layer.ipynb : LSTM which has an embedding layer (torch.Embedding) to learn the embeddings of the words.

We can provide the tensors needed to run the experiments, thus no extra libraries would need to be installed to preprocess the data. (in order to run the LSTM's fasttex needs to be installed and the embeddings for each language should be downloaded as well as spacy tokenizers for each language)
