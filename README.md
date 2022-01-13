
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NelleV/2022-mines-HPC-AI-TD/HEAD)

# hpc-ai-ml-2022

This repository holds the computer labs for the Introduction to Machine
Learning course of the 2021-2022 HPC-AI MSc
https://www.hpc-ai.mines-paristech.fr/

## Requirements

The labs were developed for Python3. All required packages are part of the
[Anaconda platform](https://www.anaconda.com/download/) so you can simply
install Anaconda3 on your machine. If you'd rather install just the required
packages with pip, that is also possible. The labs were developed for Python
3.4.3, with the following libraries:

* numpy 1.16.5
* scipy 1.2.2
* matplotlib 2.2.4
* pandas 0.22.0
* seaborn 0.9.0
* sklearn 0.19.2

## Quick start
#### Clone the 2022-mines-HPC-AI-TD repository :
```
git clone https://github.com/NelleV/2022-mines-HPC-AI-TD.git
```
#### Create the conda environment tp-ml :
```
cd 2022-mines-HPC-AI-TD
conda env create -f environment.yaml
```
#### Activate the environment tp-ml :
```
conda activate tp-ml
```
#### To show the conda environment in Jupyter Notebook, register the kernel:
```
python -m ipykernel install --user --name tp-ml --display-name "TP ML"
```
#### ps : to unregister the kernel:

```
jupyter kernelspec uninstall tp-ml
```

To __check your installation__, try launching Jupyter (e.g. by typing `jupyter
noteboook` in a shell), navigating to where you have downloaded/pulled the
first lab (.ipynb file) and opening it. In that notebook (or in a python
terminal), you should be able to run 

  ```python
  import sklearn
  import pandas
  import seaborn
  import matplotlib
  ```

## Program
* Lab 1: [Principal Component Analysis](https://github.com/NelleV/2022-mines-HPC-AI-TD/blob/master/01-PCA.ipynb) (1h)
* Lab 2: [Data normalization](https://github.com/NelleV/2022-mines-HPC-AI-TD/blob/master/02-FeatureProcessing.ipynb) (1h)
* Lab 3: [Cross validation & features](https://github.com/NelleV/2022-mines-HPC-AI-TD/blob/master/03-ProjectIntro.ipynb) 
* Lab 4: [Linear and logistic regression](https://github.com/NelleV/2022-mines-HPC-AI-TD/blob/master/04-Linear%20and%20logistic%20regressions.ipynb) (1h) 
* Lab 5: [Regularized models](https://github.com/NelleV/2022-mines-HPC-AI-TD/blob/master/05-Regularization.ipynb) (1h) 
* Lab 6: [Trees and Forests](https://github.com/NelleV/2022-mines-HPC-AI-TD/blob/master/06-TreesAndForests.ipynb) 
* Lab 7: [k-NN](https://github.com/NelleV/2022-mines-HPC-AI-TD/blob/master/07-NearestNeighbors.ipynb) 


### Acknowledgements
These notebooks are adapted from notebooks previously created with the help of
Chloé-Agathe Azencott, Judith Abecassis, Joseph Boyd, Arthur Imber, Benoit
Playe and Mihir.