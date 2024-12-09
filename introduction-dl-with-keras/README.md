To install TensorFlow for M4 chip, use miniconda:
- install from [here](https://conda-forge.org/download/)
- setup the conda env
```sh
source ~/miniconda3/bin/activate
conda create --prefix ./env python=3.8
conda activate ./env
```
- install the packages
```sh
conda install -c apple tensorflow-deps
python -m pip install tensorflow-macos tensorflow-metal
```

Then install other deps:
```sh
conda install jupyter pandas numpy matplotlib scikit-learn
```