# NodeEmbeddings

Presentation PDF and codes in Jupyter Notebook 

Running enviornment: Python 3.6, Jupyter Notebook

Here are some basic steps to setup your running environment:

1. Install Anaconda 3.7 version
2. Create a running env with necessary libaries
```
conda create --name NEEnv python=3.6 ontospy networkx pandas scipy scikit-learn pickle gensim
```
3. Activate your running env
```
conda activate NEEnv
```
4. Run the Jupyter Notebook
```
jupyter notebook
```

Notice:

For Mac, if you face some troubles opening NEEnv in you jupyter notebook, you explicitly install the new kernel using the following command in terminal

```
ipython kernel install --user --name=NEEnv
```
After this, the system will create a new kernel directory under "/Users/you_account/Library/Jupyter/kernels/NEEnv. You can then open notebook and select NEEnv as the enviornment



