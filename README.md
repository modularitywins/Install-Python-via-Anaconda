# Install-Python-via-Anaconda
How to install Python via Anaconda

### How to install Python environments on macOS using `conda`:
0. Open terminal
1. Run the following command to install anaconda
```
conda install conda
```
2. Replace `*`in the following command with the name you choose for this Python environment (e.g. `Py27`, `Py36`, etc.); replace `$` in the following command with the version number of Python environment you want to install (e.g. `2.7`, `3.6`, etc); run the following command to install Python environment with the desired version and name
```
conda create -n * python=$
```
3. Replace `*`in the following command with the name of the Python environment that you have installed (e.g. `Py27`, `Py36`, etc.); run the following command to activate the Python version you want
```
source activate *
```
4. Run your python script (e.g. `main.py`) in terminal with the following command
```
python main.py
```
5. Run the following command to deactivate the current Python version (NOT uninstall)
```
source deactivate
```

### How to install Python packages using `conda`:
Some examples of popular Python packages:
```
conda install -c conda-forge numpy
conda install -c conda-forge pandas
conda install -c conda-forge matplotlib
conda install -c conda-forge scikit-learn
conda install -c conda-forge tensorflow
```
If you don't know how install a package `*` with `conda`, simply google the following words:
```
how to install * with conda
```
It would usually follow the following format:
```
conda install -c conda-forge *
```
