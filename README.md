# Inverse FFT Calculation
This repository shows a simple demonstration of how to construct a inverse FFT model through pytorch!

<img src="figs/M1_target7.png"     alt="Target Image"     width="40%">
##


## Installation

If you manage your python environments with anaconda, you can create a new environment with

(A python version >= 3.8 is necessary since the requirment from pytorch.)
```bash
conda create -n inverseFFT python=3.8
conda activate inverseFFT
```

To install the dependencies with pip, you can use
```bash
pip install -r requirements_pip.txt
```

You may install the dependencies with conda:
```bash
conda install --file requirements_conda.txt -c pytorch -c conda-forge
```
However, due to the complex environment solving, the process may be slow and the installed packages may be unsatisfactory. 
For example, you may get a CPU version of pytorch. 
Thus, if you want to use conda, you may install a GPU version of pytorch before you install other dependencies.
See installation guideline https://pytorch.org/

## Run the code

The code was wrote on python jupyternotebook for you to have a better understanding.
```bash
inverseFFT.ipynb
```
