# Recommended Python, Data Science and ML resources
*I use this page here to share useful resources and packages I've personally tried and like. I have included even some more famous ones.*

## Python libraries
I have tested all packages myself on MacOS. 

### General

1. [black](https://pypi.org/project/black/): Neat code formatter - `black my_file.py`. There is a jupyter notebooks alternative - [nb_black](https://pypi.org/project/nb-black/) with as well. Enable it with `%load_ext nb_black` in your notebook and disable it with `%load_ext lab_black`.
2. [pre-commit](https://pre-commit.com/) A tool which performs formatting and makes checks such as pep8. Used in CI.
3. [dask](https://www.dask.org/) My favorite parallel computing lib in Python.

### Viz
1. [matplotlib-venn](https://pypi.org/project/matplotlib-venn/) I use it to make Venn diagrams.

### ML

1. [pycaret](https://pycaret.org/) **\*\*so impressed\*\*** An omnipotent ML tool, including data preprocess, automl part (selection of best model), great result overview and option to make ML pipeline from selected best model. Just check [this](https://nbviewer.org/github/pycaret/pycaret/blob/master/tutorials/Tutorial%20-%20Binary%20Classification.ipynb) example notebook.

