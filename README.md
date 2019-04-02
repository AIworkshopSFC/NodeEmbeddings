# NodeEmbeddings

Presentation PDF and codes in Jupyter Notebook 

Running enviornment: Python 3.6, Jupyter Notebook

Here are some basic steps to setup your running environment:

1. Install Anaconda 3.7 version
2. Create a running env with necessary libaries
```
conda create --name NEEnv python=3.6 networkx pandas scipy scikit-learn gensim matplotlib
```
3. install ontospy
```
pip install ontospy
```
4. Activate your running env
```
conda activate NEEnv
```
5. Run the Jupyter Notebook
```
jupyter notebook
```

Notice:

For Mac, if you face some troubles opening NEEnv in you jupyter notebook, you explicitly install the new kernel using the following command in terminal

```
ipython kernel install --user --name=NEEnv
```
After this, the system will create a new kernel directory under "/Users/you_account/Library/Jupyter/kernels/NEEnv. You can then open notebook and select NEEnv as the enviornment



Code References:

1.Reference implementation of Ontospy. http://lambdamusic.github.io/Ontospy/

2.Reference implementation of node2vec. Author: Aditya Grover For more details, refer to the paper: node2vec: Scalable Feature Learning for Networks Aditya Grover and Jure Leskovec Knowledge Discovery and Data Mining (KDD), 2016. https://github.com/aditya-grover/node2vec

3.Reference implementation of link prediction task using fb data: Lucas Hu https://github.com/lucashu1
