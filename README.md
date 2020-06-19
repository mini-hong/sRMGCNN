# sRMGCNN
Project for Graph Convolutional Network

Paper : 

Federico Monti, Michael M. Bronstein, and Xavier Bresson, ``Geometric Matrix Completion with Recurrent Multi-Graph Neural Networks'', NIPS 2017

The code is based on https://github.com/fmonti/mgcnn/

## How to run

Make a new virtualenv (Recommended)
```sh
virtualenv venv --python=python3.6 (--system-site-packages)
```

Install packages required
```sh
source venv/bin/activate
pip install tensorflow==1.13
pip install joblib h5py scipy matplotlib
```

Now you are free to run the project files.

Note that there are separate .ipynb files for each of dataset, in mgcnn/Notebooks folder.
