# Udacity AWS Machine Learning Foundations Course

https://classroom.udacity.com/nanodegrees/nd065

## Jupyter Instructions

```sh
# Install conda and mamba
brew install --cask miniconda
conda init zsh
conda install mamba -n base -c conda-forge

# Setup environment
mamba create --name testenv numpy pandas jupyterlab
conda activate testenv

# Install packages
mamba install -c conda-forge jupyterlab

jupyter lab
```