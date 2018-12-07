# {{cookiecutter.project_name}}

{{cookiecutter.description}}

### To create conda enviornment:
------------

``` bash
$(from scratch) make create_environment
$(from existing) make requirements
```

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
