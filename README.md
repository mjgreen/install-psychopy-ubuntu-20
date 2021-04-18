# howto_install_psychopy_on_ubuntu_20_04

## Get the wheel for wxPython
* https://extras.wxpython.org/wxPython4/extras/linux/gtk3/ubuntu-18.04/wxPython-4.1.1-cp36-cp36m-linux_x86_64.whl

## Get miniconda
* https://repo.anaconda.com/miniconda/Miniconda3-py39_4.9.2-Linux-x86_64.sh
* install it

## Use conda to create a python 3.6 environment
* conda create -n python3.6 python=3.6
* conda activate python36
* pip install /path/to/wxPythonwheel
* pip install psychopy                   # currently gets 2020.1.3
* pip install sounddevice PTB pyo pygame # sound libraries are required

