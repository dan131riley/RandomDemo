# Random Number demos for CoDaS 2018

https://ml-front.nautilus.optiputer.net/index.html

# Getting started
To be able to run the demo, you are going to need a laptop with Miniconda (a minimal version of Anaconda) and several Python packages installed, or use the resources used for the PyTorch tutorial.

## Download and install Miniconda
Please go to the following website: https://conda.io/miniconda.html
download and install *the latest* Miniconda version for Python 3.6 for your operating system. 
```bash
wget <http:// link to miniconda>
sh <miniconda .sh>
```


After that, type:

```bash
conda --help
```

and read the manual.

## Check-out the git repository with the exercise 
Once Miniconda is ready, checkout the course repository and
and proceed with setting up the environment:

```bash
git clone https://github.com/dan131riley/RandomDemo.git 
```

## Create isolated Miniconda environment
Change into the course folder, then type:

```bash
cd RandomDemo
conda env create -f conda-envt.yml
source activate codas-random
```


## Start jupyter notebook

Finally, start the jupyter notebook, if working on laptop do:

```bash
jupyter notebook
```
