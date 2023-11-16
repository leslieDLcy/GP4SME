SME
==============================

Assignment for SME borrowing history


## how submission

As answers to the practical assignment, two files, as listed below, are submitted:

1. A [Jupyter notebook file](https://nbviewer.org/github/leslieDLcy/SME/blob/main/notebooks/SME_assignment_byYuChen.ipynb#) as a one-stop solution containing code and explanation. It can be better viewed via `nbviewer` at [this address](https://nbviewer.org/github/leslieDLcy/SME/blob/main/notebooks/SME_assignment_byYuChen.ipynb#). The original `.ipynb` file is stored in this repository [here](notebooks/SME_assignment_byYuChen.ipynb).

2. A PDf report clearly summarizing the procedures and futher thoughts on Machine Learning strategies that can deliver more possibilities for this assignment. 


## on organising the code

Throughout this analysis, I meant to write library codes that can serve as recipes, for instance, to solve a certain data problem, create a model, generate a figure, etc. Most importantly, these library codes can be re-used by others (e.g. team members or clients) later on, as in being adopted in user code. Notably, these library codes can be easily packaged into a Python package, facilitating the sharing and usage by others


## on processing data

> Python functions are written as recipes to solve a respective data problem. Most importanly, these functions can be chaining together using Pandas's **chaining** mechanism.

> As such, a one-stop function can be created, by chaining, to process the raw data and then save the cleaned data into the `/data/processed` directory.

> Later on, modellers can directly import this processed clean dataset from disk, saving the trouble for processing data each time.



--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
