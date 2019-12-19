# Document Classification Using Deep Neural Networks

This is a Machine learning project to perform text classification on the famous Reuters corpus using Deep Neural Networks. In this, we have
read some text files and classified them according to their labels. "Data" folder contains all the files from the Reuters corpus that are
required to perform classification. There is more information about this dataset available on  http://disi.unitn.it/moschitti/corpora.htm.

# Steps involved:
1. A function to extract a Pandas's Dataframe containing: (1) headline, (2) text, (3) bip:topics,(4) dc.date.published, (5) itemid, 
(6) XMLfilename
2. A function to perform text preprocessing including removal of stop words, removal of all the words except nouns, stemming and lemmetization
3. A function to cluster all the documents using Elbow method, and assign a cluster-id to each document. After clustering documents, we generated a different 
classifier for each identified cluster.
4. A function to evaluate the quality of your clusters and visualize a TSNE plot of clusters
5. Generated a set of features for each extracted cluster separately using deep neural networks- CNN and Stacked Autoencoder. 
6. Improved the classification approach by using new features and taking advantage of deep neural networks.
