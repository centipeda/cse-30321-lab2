# cse-30321-lab02

CSE 30321: Computer Architecture
Lab 02

## installation

I've modified the notebooks so they should run locally... getting this to work on Windows is kind of a pain in the neck, so this is how I did it:

1. install [Conda](https://docs.conda.io/en/latest/)
1. open up the Anaconda Prompt
1. install [Jupyter](https://jupyter.org/install) -- `conda install -c conda-forge jupyterlab`
1. install [Tensorflow](https://docs.anaconda.com/anaconda/user-guide/tasks/tensorflow/):
`conda create -n tf-gpu tensorflow-gpu` then `conda activate tf-gpu`
1. install Git for Conda -- `conda install -c anaconda git`
1. clone the repo wherever -- `git clone https://github.com/centipeda/cse-30321-lab2.git` 
1. move into the repo directory
1. run `jupyter notebook` in the repo directory to launch Jupyter
