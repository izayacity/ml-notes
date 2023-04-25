Required python packages

```
pip3 install numpy
pip3 install matplotlib
pip3 install scipy
pip3 install tqdm
pip3 install scikit-learn
```

Installation using conda

However, the recommended way of configuring your system is by using a conda environment.

We recommend that you install the latest version of Miniconda from https://docs.conda.io/en/latest/miniconda.html.

You can then create a conda environment for this course using

```
conda create -n 6.86x python=3.8
```

To activate this environment, use
```
conda activate 6.86x
```
Finally, install all of the required packages:
```
conda install pytorch -c pytorch
conda install numpy
conda install matplotlib
conda install scipy
conda install tqdm
conda install scikit-learn
```