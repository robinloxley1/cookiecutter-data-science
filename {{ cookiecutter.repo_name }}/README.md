# {{cookiecutter.project_name}}

{{cookiecutter.description}}

### To create conda enviornment:
------------

``` bash
$(for the 1st time ) make create_environment
$(for subsequential) make requirements
```

### To start working:
------------

``` bash
$ source activate {{cookiecutter.project_name}}
$ conda install your-own-package
```

### To export/import conda environment:
------------

``` bash
$ conda env export > environment.yml
```
