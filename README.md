# cae-environments

climakitae related development and deployment files

# Docker image Makefiles

Makefiles for spinning up Docker images

# Conda environment lock files

Conda-lock build environment files for testing in climakitae and climakitaegui

This repo contains pinned environmental.yml files used in conjunction with conda-lock python package to generate conda-lock files used by testing environment in climakitae and climakitaegui.

Uses conda-lock version 2.4.2

Example command used to generate lock file:

```
conda-lock --kind=explicit -f environment.yml -p linux-64
```
