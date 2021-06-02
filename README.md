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
# conda env create -f C:\caiyongji\ML\tf2.yml 
conda info --envs
conda env remove --name tf2021
conda create -n tf2021
conda activate tf2021
conda install python=3.7.10
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

### tensorflow_addons

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow_addons

### gym[atari]

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple gym[atari]


## 20210519

· conda config --add envs_dirs C:\ML\envs
· conda config --show
· conda env remove --name tf202105
· conda create -n tf202105
· conda info --envs
· conda activate tf202105
· conda install python=3.7.10

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tfx

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow-datasets tf-agents matplotlib pandas scikit-learn scikit-image ipython jupyter keras gym lxml xlrd openpyxl sqlalchemy jupyterlab seaborn tabulate pydot pydotplus tensorflow-model-remediation












Successfully installed MarkupSafe-2.0.1 Send2Trash-1.5.0 absl-py-0.12.0 apache-beam-2.29.0 argon2-cffi-20.1.0 astunparse-1.6.3 async-generator-1.10 attrs-20.3.0 avro-python3-1.9.2.1 backcall-0.2.0 bleach-3.3.0 cachetools-4.2.2 cffi-1.14.5 chardet-4.0.0 click-7.1.2 colorama-0.4.4 crcmod-1.7 decorator-5.0.9 defusedxml-0.7.1 dill-0.3.1.1 docker-4.4.4 docopt-0.6.2 entrypoints-0.3 fastavro-1.4.1 fasteners-0.16 flatbuffers-1.12 future-0.18.2 gast-0.3.3 google-api-core-1.27.0 google-api-python-client-1.12.8 google-apitools-0.5.31 google-auth-1.30.0 google-auth-httplib2-0.1.0 google-auth-oauthlib-0.4.4 google-cloud-aiplatform-0.7.1 google-cloud-bigquery-1.28.0 google-cloud-bigtable-1.7.0 google-cloud-core-1.6.0 google-cloud-datastore-1.15.3 google-cloud-dlp-1.0.0 google-cloud-language-1.3.0 google-cloud-pubsub-1.7.0 google-cloud-spanner-1.19.1 google-cloud-storage-1.38.0 google-cloud-videointelligence-1.16.1 google-cloud-vision-1.0.0 google-crc32c-1.1.2 google-pasta-0.2.0 google-resumable-media-1.3.0 googleapis-common-protos-1.53.0 grpc-google-iam-v1-0.12.3 grpcio-1.32.0 grpcio-gcp-0.2.2 h5py-2.10.0 hdfs-2.6.0 httplib2-0.17.4 idna-2.10 importlib-metadata-4.0.1 ipykernel-5.5.5 ipython-7.23.1 ipython-genutils-0.2.0 ipywidgets-7.6.3 jedi-0.18.0 jinja2-2.11.3 joblib-0.14.1 jsonschema-3.2.0 jupyter-client-6.2.0 jupyter-core-4.7.1 jupyterlab-pygments-0.1.2 jupyterlab-widgets-1.0.0 keras-preprocessing-1.1.2 keras-tuner-1.0.1 kubernetes-11.0.0 markdown-3.3.4 matplotlib-inline-0.1.2 mistune-0.8.4 ml-metadata-0.30.0 ml-pipelines-sdk-0.30.0 nbclient-0.5.3 nbconvert-6.0.7 nbformat-5.1.3 nest-asyncio-1.5.1 notebook-6.4.0 numpy-1.19.5 oauth2client-4.1.3 oauthlib-3.1.0 opt-einsum-3.3.0 packaging-20.9 pandas-1.2.4 pandocfilters-1.4.3 parso-0.8.2 pickleshare-0.7.5 portpicker-1.3.9 prometheus-client-0.10.1 prompt-toolkit-3.0.18 proto-plus-1.18.1 protobuf-3.17.0 pyarrow-2.0.0 pyasn1-0.4.8 pyasn1-modules-0.2.8 pycparser-2.20 pydot-1.4.2 pygments-2.9.0 pymongo-3.11.4 pyparsing-2.4.7 pyrsistent-0.17.3 python-dateutil-2.8.1 pytz-2021.1 pywin32-227 pywinpty-1.1.1 pyyaml-5.4.1 pyzmq-22.0.3 requests-2.25.1 requests-oauthlib-1.3.0 rsa-4.7.2 scikit-learn-0.24.2 scipy-1.6.3 six-1.15.0 tabulate-0.8.9 tensorboard-2.5.0 tensorboard-data-server-0.6.1 tensorboard-plugin-wit-1.8.0 tensorflow-2.4.1 tensorflow-data-validation-0.30.0 tensorflow-estimator-2.4.0 tensorflow-hub-0.9.0 tensorflow-metadata-0.30.0 tensorflow-model-analysis-0.30.0 tensorflow-serving-api-2.4.1 tensorflow-transform-0.30.0 termcolor-1.1.0 terminado-0.10.0 terminaltables-3.1.0 testpath-0.5.0 tfx-0.30.0 tfx-bsl-0.30.0 threadpoolctl-2.1.0 tornado-6.1 tqdm-4.60.0 traitlets-5.0.5 typing-extensions-3.7.4.3 uritemplate-3.0.1 urllib3-1.26.4 wcwidth-0.2.5 webencodings-0.5.1 websocket-client-1.0.0 werkzeug-2.0.1 widgetsnbextension-3.5.1 wrapt-1.12.1 zipp-3.4.1

Successfully installed Pillow-8.2.0 PyWavelets-1.1.1 anyio-3.1.0 babel-2.9.1 cloudpickle-1.6.0 cycler-0.10.0 decorator-4.4.2 dm-tree-0.1.6 et-xmlfile-1.1.0 gin-config-0.4.0 greenlet-1.1.0 gym-0.18.3 imageio-2.9.0 importlib-resources-5.1.3 json5-0.9.5 jupyter-1.0.0 jupyter-console-6.4.0 jupyter-server-1.7.0 jupyterlab-3.0.16 jupyterlab-server-2.5.2 keras-2.4.3 kiwisolver-1.3.1 lxml-4.6.3 matplotlib-3.4.2 nbclassic-0.2.8 networkx-2.5.1 openpyxl-3.0.7 promise-2.3 pydotplus-2.0.2 pyglet-1.5.15 qtconsole-5.1.0 qtpy-1.9.0 scikit-image-0.18.1 seaborn-0.11.1 sniffio-1.2.0 sqlalchemy-1.4.15 tensorflow-datasets-4.3.0 tensorflow-probability-0.12.2 tf-agents-0.8.0 tifffile-2021.4.8 xlrd-2.0.1
