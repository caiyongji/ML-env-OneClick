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


## 20210602

conda config --add envs_dirs C:\ML\envs
conda config --show
conda env remove --name tf202106
conda create -n tf202106
conda info --envs
conda activate tf202106
conda install python=3.7.10

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tfx

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow-datasets tf-agents matplotlib pandas scikit-learn scikit-image ipython jupyter keras gym lxml xlrd openpyxl sqlalchemy jupyterlab seaborn tabulate pydot pydotplus tensorflow-model-remediation

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple featuretools 


## 20220210
#### for windows
HKEY_CURRENT_USER\Console QuickEdit 1 -> 0

conda config --add envs_dirs C:\ML\envs

conda config --show
conda info --envs
conda env remove --name env202202
conda create -n env202202 --yes
conda activate env202202
conda install python=3.8.12 --yes

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tfx 

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow-datasets tf-agents matplotlib pandas scikit-learn scikit-image ipython jupyter keras gym lxml xlrd openpyxl sqlalchemy jupyterlab seaborn tabulate pydot pydotplus tensorflow-model-remediation 

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple featuretools

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple torch torchvision torchaudio

--------
Successfully installed MarkupSafe-2.0.1 Send2Trash-1.8.0 absl-py-1.0.0 apache-beam-2.36.0 argon2-cffi-21.3.0 argon2-cffi-bindings-21.2.0 astunparse-1.6.3 attrs-20.3.0 backcall-0.2.0 bleach-4.1.0 cachetools-4.2.4 cffi-1.15.0 charset-normalizer-2.0.11 click-7.1.2 cloudpickle-2.0.0 colorama-0.4.4 crcmod-1.7 debugpy-1.5.1 decorator-5.1.1 defusedxml-0.7.1 dill-0.3.1.1 docker-4.4.4 docopt-0.6.2 entrypoints-0.4 fastavro-1.4.9 fasteners-0.17.3 flatbuffers-2.0 gast-0.4.0 google-api-core-1.31.5 google-api-python-client-1.12.10 google-apitools-0.5.31 google-auth-1.35.0 google-auth-httplib2-0.1.0 google-auth-oauthlib-0.4.6 google-cloud-aiplatform-1.10.0 google-cloud-bigquery-2.32.0 google-cloud-bigquery-storage-2.11.0 google-cloud-bigtable-1.7.0 google-cloud-core-1.7.2 google-cloud-datastore-1.15.3 google-cloud-dlp-3.6.0 google-cloud-language-1.3.0 google-cloud-pubsub-2.9.0 google-cloud-pubsublite-1.3.0 google-cloud-recommendations-ai-0.2.0 google-cloud-spanner-1.19.1 google-cloud-storage-1.44.0 google-cloud-videointelligence-1.16.1 google-cloud-vision-1.0.0 google-crc32c-1.3.0 google-pasta-0.2.0 google-resumable-media-2.2.1 googleapis-common-protos-1.54.0 grpc-google-iam-v1-0.12.3 grpcio-1.43.0 grpcio-gcp-0.2.2 grpcio-status-1.43.0 h5py-3.6.0 hdfs-2.6.0 httplib2-0.19.1 idna-3.3 importlib-metadata-4.10.1 importlib-resources-5.4.0 ipykernel-6.9.0 ipython-7.31.1 ipython-genutils-0.2.0 ipywidgets-7.6.5 jedi-0.18.1 jinja2-3.0.3 joblib-0.14.1 jsonschema-4.4.0 jupyter-client-7.1.2 jupyter-core-4.9.1 jupyterlab-pygments-0.1.2 jupyterlab-widgets-1.0.2 keras-2.7.0 keras-preprocessing-1.1.2 keras-tuner-1.1.0 kt-legacy-1.0.4 kubernetes-12.0.1 libclang-13.0.0 libcst-0.4.1 markdown-3.3.6 matplotlib-inline-0.1.3 mistune-0.8.4 ml-metadata-1.6.0 ml-pipelines-sdk-1.6.1 mypy-extensions-0.4.3 nbclient-0.5.10 nbconvert-6.4.2 nbformat-5.1.3 nest-asyncio-1.5.4 notebook-6.4.8 numpy-1.21.5 oauth2client-4.1.3 oauthlib-3.2.0 opt-einsum-3.3.0 orjson-3.6.6 overrides-6.1.0 packaging-20.9 pandas-1.4.0 pandocfilters-1.5.0 parso-0.8.3 pickleshare-0.7.5 portpicker-1.5.0 prometheus-client-0.13.1 prompt-toolkit-3.0.27 proto-plus-1.20.0 protobuf-3.19.4 psutil-5.9.0 pyarrow-5.0.0 pyasn1-0.4.8 pyasn1-modules-0.2.8 pycparser-2.21 pydot-1.4.2 pygments-2.11.2 pymongo-3.12.3 pyparsing-2.4.7 pyrsistent-0.18.1 python-dateutil-2.8.2 pytz-2021.3 pywin32-227 pywinpty-2.0.2 pyyaml-5.4.1 pyzmq-22.3.0 requests-2.27.1 requests-oauthlib-1.3.1 rsa-4.8 scipy-1.8.0 six-1.16.0 tensorboard-2.8.0 tensorboard-data-server-0.6.1 tensorboard-plugin-wit-1.8.1 tensorflow-2.7.1 tensorflow-data-validation-1.6.0 tensorflow-estimator-2.7.0 tensorflow-hub-0.12.0 tensorflow-io-gcs-filesystem-0.24.0 tensorflow-metadata-1.6.0 tensorflow-model-analysis-0.37.0 tensorflow-serving-api-2.7.0 tensorflow-transform-1.6.0 termcolor-1.1.0 terminado-0.13.1 testpath-0.5.0 tfx-1.6.1 tfx-bsl-1.6.0 tornado-6.1 traitlets-5.1.1 typing-extensions-4.0.1 typing-inspect-0.7.1 typing-utils-0.1.0 uritemplate-3.0.1 urllib3-1.26.8 wcwidth-0.2.5 webencodings-0.5.1 websocket-client-1.2.3 werkzeug-2.0.3 widgetsnbextension-3.5.2 wrapt-1.13.3 zipp-3.7.0

Successfully installed PyWavelets-1.2.0 anyio-3.5.0 babel-2.9.1 cycler-0.11.0 dm-tree-0.1.6 et-xmlfile-1.1.0 fonttools-4.29.1 gin-config-0.5.0 greenlet-1.1.2 gym-0.21.0 imageio-2.15.0 json5-0.9.6 jupyter-1.0.0 jupyter-console-6.4.0 jupyter-server-1.13.5 jupyterlab-3.2.9 jupyterlab-server-2.10.3 kiwisolver-1.3.2 lxml-4.7.1 matplotlib-3.5.1 mock-4.0.3 nbclassic-0.3.5 networkx-2.6.3 openpyxl-3.0.9 pillow-9.0.1 promise-2.3 pydotplus-2.0.2 pywinpty-1.1.6 qtconsole-5.2.2 qtpy-2.0.1 scikit-image-0.19.1 scikit-learn-1.0.2 seaborn-0.11.2 sniffio-1.2.0 sqlalchemy-1.4.31 tabulate-0.8.9 tensorflow-datasets-4.5.2 tensorflow-model-remediation-0.1.5 tensorflow-probability-0.15.0 tf-agents-0.11.0 threadpoolctl-3.1.0 tifffile-2022.2.9 tqdm-4.62.3 xlrd-2.0.1

Successfully installed dask-2022.1.1 distributed-2022.1.1 featuretools-1.4.1 fsspec-2022.1.0 heapdict-1.0.1 locket-0.2.1 msgpack-1.0.3 pandas-1.3.5 partd-1.2.0 sortedcontainers-2.4.0 tblib-1.7.0 toolz-0.11.2 woodwork-0.11.2 zict-2.0.0

Successfully installed torch-1.10.2 torchaudio-0.10.2 torchvision-0.11.3
