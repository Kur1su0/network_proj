# Readme

Using machine learning related methods to dectect malwares based on binary image & opcode.

- gen_features: feature extraction.
- ?.py : traditional machine learning.
- nn.ipynb: CNN (VGG-16) and MLP.

## Environment

python=3.7.10

Required packages: (any relatively new version should work) 

* numpy
* Pillow
* pandas
* sklearn
* keras
* seaborn

## Data

We only included the n-gram opcode features in this repo.

See /u/zw9ga/net_proj/data/subtrain on cs portal for malware files and malware images. 