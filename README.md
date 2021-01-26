This repository contains files containing an experiment conducted as part of my master's work (a description will be added later). To reproduce the results, do the following:
1. Write the paths to the data folder and to the dataset, which will be recorded and used in work, to *config.py*.
2. Run the *parse.ipynb* file. The files in the config date will be parsed and the final dataset will be constructed.
3. Run the *dataset statistics.ipynb* file (optional): it contains some statistics on the data.
4. Run the *clean.py* file: texts cleaned of noisy data will be formed.
5. Run one of the following files: *Word2Vec.ipynb*, *fastText.ipynb*, *BERT.ipynb* to get the required vector representation of the texts.
6. To calculate metrics, run *agglomerative clustering.ipynb* and *kNN.ipynb*. In the top cell it is necessary to indicate which tokens are used.

For clarity, the project structure is shown in the image:<br>
<img src="/images/structure.jpg" alt="structure" width="400"/>
