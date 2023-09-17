# TensorFlow-in-GPT-4-advanced-data-analysis-mode
Install TensorFlow on GPT-4 (advanced data analysis mode), or any other not pre-installed libraries.

Note: GPT-4 has a limit of maximum size of file(s) upload at one time. So we choose TensorFlow==2.3.0(manylinux;cp38), and uploads all the dependencies(~370MB in total) and instruct GPT to install it.

## Steps
**WIP**

First, create a venv on a similiar virtural machine.(python3.8;manylinux) and activate it. 

Then,use 'pip download -d /path/to/your/folder tensorflow==2.3.0' to download the whole files.

Upload .whl files and instructs GPT-4 to install it step by step.

Due to kernel restart, the first installation was not successful. But it's almost finished(all denpendencies are installed except tf2.3.0). I'll try again.

<img width="499" alt="Failed" src="https://github.com/sszzz830/TensorFlow-in-GPT-4-advanced-data-analysis-mode/assets/32834442/127baa6b-bfcb-4312-bec9-76051de2f73a">
