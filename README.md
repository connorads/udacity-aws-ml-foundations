# Udacity AWS Machine Learning Foundations Course

https://classroom.udacity.com/nanodegrees/nd065

## Jupyter Instructions

```sh
# Install conda and mamba
brew install --cask miniconda
conda init zsh
conda install mamba -n base -c conda-forge

# Disable base activation (prevent conflict with pyenv)
conda config --set auto_activate_base false

# Setup environment
mamba create --name testenv numpy pandas jupyterlab
conda activate testenv

# Install packages
mamba install -c conda-forge jupyterlab
mamba install -c conda-forge pytest matplotlib

jupyter lab
```