# {{cookiecutter.project_name}}

{{cookiecutter.description}}

### To create conda enviornment:
------------

``` bash
# for the 1st time install cookiecutter basic requirements from default environment.yml
$ make create_environment
$ source activate {{cookiecutter.project_name}}
$({{cookiecutter.project_name}}) conda install jupyter
$ source deactive # a must to use root env; ensure conda install nb_conda_kernels at root env
$ jupyter notebook # be able to switch kernels to [conda env:{{cookiecutter.project_name}}]
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
$(for subsequential import) make requirements
```
