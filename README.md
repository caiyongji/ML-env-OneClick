# ML-env-OneClick
 One Click to configure ML environment

## install miniconda
[https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

## config conda env path
```
conda config --add envs_dirs C:\caiyongji\ML\envs 
conda config --show
```
## create env by .yml file
```
conda env create -f C:\caiyongji\ML\environment-windows.yml 
conda info --envs
```
