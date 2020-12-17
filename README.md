# ML-env-OneClick
 One Click to configure ML environment

## install miniconda
[https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

## config conda env path
```
conda config --add envs_dirs C:\caiyongji\ML\envs 
conda config --set pip_interop_enabled True
conda config --show
conda init
```
## create env by .yml file
```
conda env create -f C:\caiyongji\ML\tf2.yml 
conda info --envs
```

## pip install 
```
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow-cpu tensorflow-datasets tf-agents matplotlib pandas scikit-learn scikit-image ipython jupyter keras gym lxml xlrd openpyxl sqlalchemy jupyterlab seaborn tabulate pydot pydotplus
```

### graphviz
1. pip install -i https://pypi.tuna.tsinghua.edu.cn/simple graphviz
2. install for Windows:https://www2.graphviz.org/Packages/stable/windows/10/msbuild/Release/Win32/graphviz-2.44.1-win32.zip
3. config `bin` to PATH. eg: C:\caiyongji\ML\Graphviz\bin

### tabulate
pandas to markdown

### pydot pydotplus
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pydot pydotplus