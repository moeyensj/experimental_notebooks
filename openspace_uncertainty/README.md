### OpenSpace Project - Orbital Uncertainty Visualization

To install the required packages:

```shell
pip install --user -r requirements.txt
```

If using `conda`, a fresh environment can be made with a command like:
```shell
conda create -n openspace_py310 python=3.10 
conda activate openspace_py310
pip install -r requirements.txt
```

To be able to propagate orbits, you will need to install PYOORB via conda:
```shell
conda install -c conda-forge openorb
```

However, this repository already comes with a pre-computed set of orbit propagations for a few objects.
