# Cookiecutter Data Science

A fork created by Leo/

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._


#### [Project homepage](http://drivendata.github.io/cookiecutter-data-science/)


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/robinloxley1/cookiecutter-data-science.git 


### To create conda enviornment:
------------

``` bash
$(from scratch) make create_environment
$(from existing) conda env create -f=environment.yml

### To start working:
------------

``` bash
$ conda activate {{cookiecutter.project_name}}
$ conda install your-own-package
```

### To export/import conda environment:
------------

``` bash
$ conda env export > environment.yml
```
