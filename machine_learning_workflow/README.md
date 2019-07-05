# Model Workflow and Algorithm Comparison

## Setup instructions

### On your machine

With Anaconda:

```
conda install --file requirements.txt -c conda-forge
```

With pip:

```
pip install -r requirements.txt
```

#### Running

```
jupyter notebook
```
This is a supervised learning classification example adapted from a model interpretability class at Pycon2019.
I explore several different algorithms and compare metrics accross models, using CV and Gridsearch in SKlearn.

Techniques like one hot encoding and sk learn pipeline are leveraged. Grid search and cross validation are used to find best hyper parameters.

Metrics include balanced accuracy, auc/roc, fl score, precision and recall to compare models.
