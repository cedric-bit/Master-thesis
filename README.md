# Master-thesis
Deep Scattering network

The thesis aims to develop a methodology based on deep Scattering  networks to radically improve the quality of denoising and classification of seismic data provided by the DAS. In this study, an approach has been developed to reliably detect and categorise CO2 gas bubble signals by exploiting the ability of scattering networks to extract essential signal features in low-noise space. In addition, the paper describes the use of dimensionality reduction and unsupervised clustering techniques to identify specific patterns characteristic of magma bubble activity.

## Step 1 Data preprocessing

```shell
conda create --name obspy-env python
conda activate obspy-env
pip install obspy
pip install scatseisnet
conda install matplotlib scikit-learn
```

To convert my seismic data, I use [ObsPy](https://docs.obspy.org/tutorial/index.html), a powerful and efficient tool.

## Step 2 Compute Scattering coeficient
pip install scatseisnet

For more information on ScatSeisNet, please refer to the [ScatSeisNet documentation](https://scatseisnet.readthedocs.io/en/latest/autoapi/scatseisnet/index.html).

## Step 3 Dimensionality reduction with PCA and ICA

conda install matplotlib scikit-learn

## Step 4 Clustering with K-mean
conda install matplotlib scikit-learn

from sklearn.cluster import KMeans
