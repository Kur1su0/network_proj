# Network Security & Privacy Final Project

Using machine learning to classify malware based on malware images & n-gram opcode.

- gen_features.ipynb: Data sampling, image and OpCode feature extraction.
- rf_xxx.ipynb / svm_xxx.ipynb : Random Forest and Support Vector Machine.
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
* subprocess.call  (for visulization only)
* IPython.display.Image  (for visulization only)

## Data

We only included the n-gram opcode features in this repo.
See /u/zw9ga/net_proj/data/subtrain on cs portal for malware files and malware images. 
