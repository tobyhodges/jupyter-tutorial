# Jupyter Mini-Tutorial
## EMBL Coding Club 02-Feb-2017

#### Introduction
- what am Jupyter notebook?
- installing Jupyter
  - prerequisites -> only Python needed (2.7 or >=3.3), and a web browser
  - comes with anaconda or you can use miniconda/`pip`
- running Jupyter notebook
  - `jupyter notebook`
- [list of available kernels](https://github.com/ipython/ipython/wiki/IPython-kernels-for-other-languages)
  - want to use a different language? now's the time!

#### Interface
- overview of interface:
  - code execution and editing, ctrl-z
  - tab-completion, syntax highlighting, dropdowns, ...
  - visible output (use `;` to suppress)
  - help interface
  - [Markdown](https://daringfireball.net/projects/markdown/syntax) cells (includes LaTeX)

#### Tips & Tricks
- system commands
  - `!ls`
  - `!cd`
  - `!find`
- 'magic commands' with `%`
  - `%alias` = create command/function alias
  - `%debug` = open interactive debugger
  - `%edit` = open editor & execute after close
  - `%env` = set environment variables
  - `%matplotlib inline` = embed plots/images in notebook
  - `%store` = save data for use in another notebook
  - `%time/%timeit` = time execution of function call
- widgets
  - `interact` = interactively adjust arguments to functions (Python only?)
  - `Map`
  - viewing notebooks
    - [nbviewer](https://nbviewer.jupyter.org) & [GitHub notebook rendering](https://github.com/tobyhodges/ITPP/blob/master/4_PlottingData.ipynb)
    - [binder](http://mybinder.org) for interactive notebook sessions served remotely
- extensions
  - [rise](https://github.com/damianavila/RISE) & [Notebook Present](https://docs.continuum.io/anaconda/jupyter-notebook-extensions) = notebook -> slideshow
  - [loads more](http://jupyter-contrib-nbextensions.readthedocs.io/en/latest/)

#### Recommended Reading
- [28 Jupyter Notebook Tips & Tricks](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
- [`interact` docs](http://ipywidgets.readthedocs.io/en/latest/examples/Using%20Interact.html)
