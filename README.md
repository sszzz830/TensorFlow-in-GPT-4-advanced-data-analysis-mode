# TensorFlow-in-GPT-4-advanced-data-analysis-mode
Install TensorFlow on GPT-4 (advanced data analysis mode), or any other not pre-installed libraries.

Note: GPT-4 has a limit of maximum size and amount of file(s) upload at one time(Max 512MB,10files). So we choose TensorFlow==2.3.0(manylinux;cp38), and uploads all the dependencies(~370MB in total) in 4 turns and instruct GPT to install it.

## Steps
**WIP**

First, create a venv on a similiar virtural machine.(python3.8;manylinux) and activate it. 

Then,use 'pip download -d /path/to/your/folder tensorflow==2.3.0' to download the whole files.

```
pyasn1_modules-0.3.0-py2.py3-none-any.whl
idna-3.4-py3-none-any.whl
zipp-3.16.2-py3-none-any.whl
protobuf-4.24.3-cp37-abi3-manylinux2014_x86_64.whl
opt_einsum-3.3.0-py3-none-any.whl
google_pasta-0.2.0-py3-none-any.whl
certifi-2023.7.22-py3-none-any.whl
importlib_metadata-6.8.0-py3-none-any.whl
gast-0.3.3-py2.py3-none-any.whl
google_auth-2.23.0-py2.py3-none-any.whl
pyasn1-0.5.0-py2.py3-none-any.whl
All-Dependencies.txt
wheel-0.41.2-py3-none-any.whl
oauthlib-3.2.2-py3-none-any.whl
Markdown-3.4.4-py3-none-any.whl
tensorboard_data_server-0.7.1-py3-none-manylinux2014_x86_64.whl
MarkupSafe-2.1.3-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
urllib3-1.26.16-py2.py3-none-any.whl
requests-2.31.0-py3-none-any.whl
scipy-1.4.1-cp38-cp38-manylinux1_x86_64.whl
charset_normalizer-3.2.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
absl_py-1.4.0-py3-none-any.whl
tensorboard-2.14.0-py3-none-any.whl
termcolor-2.3.0-py3-none-any.whl
rsa-4.9-py3-none-any.whl
google_auth_oauthlib-1.0.0-py2.py3-none-any.whl
wrapt-1.15.0-cp38-cp38-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl
tensorflow_estimator-2.3.0-py2.py3-none-any.whl
cachetools-5.3.1-py3-none-any.whl
numpy-1.18.5-cp38-cp38-manylinux1_x86_64.whl
astunparse-1.6.3-py2.py3-none-any.whl
requests_oauthlib-1.3.1-py2.py3-none-any.whl
tensorflow-2.3.0-cp38-cp38-manylinux2010_x86_64.whl
six-1.16.0-py2.py3-none-any.whl
setuptools-68.2.2-py3-none-any.whl
h5py-2.10.0-cp38-cp38-manylinux1_x86_64.whl
grpcio-1.58.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
Keras_Preprocessing-1.1.2-py2.py3-none-any.whl
werkzeug-2.3.7-py3-none-any.whl
```

Upload .whl files and instructs GPT-4 to install it step by step.

Due to kernel restart, the first installation was not successful. But it's almost finished(all denpendencies are installed except tf2.3.0). I'll try again.

<img width="499" alt="Failed" src="https://github.com/sszzz830/TensorFlow-in-GPT-4-advanced-data-analysis-mode/assets/32834442/127baa6b-bfcb-4312-bec9-76051de2f73a">
