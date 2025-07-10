# Setting up climakitae computational environment on your local machine 

## Docker 
We have included a Makefile for your convenience that faciliates setting up a computational environment using Docker from which you can run climakitae. You'll need Docker installed on your machine. See the [Docker website](https://docs.docker.com/engine/install/) for more instructions. 

### How to use a Makefile 
From your terminal, from the directory containing the Makefile: 
```
make local 
```

## Conda 
To build the conda environment, use the following command, modifying it as neccessary to use the appropriate lockfile for your machine: 
```
conda create -n climakitae --file conda-osx-64.lock
conda activate climakitae
```
