# Paddle 2.0.0 for the Jetson Nano
Paddle installation files for the Jetson Nano<br/>
For the installation guide see [Install Paddle 2.0.0](https://qengineering.eu/install-paddle-on-jetson-nano.html) <br/>
## Dependency
```
# install dependencies
$ sudo apt-get install cmake wget
$ sudo apt-get install libatlas-base-dev libopenblas-dev libblas-dev
$ sudo apt-get install liblapack-dev patchelf gfortran
$ sudo -H pip3 install Cython
$ sudo -H pip3 install -U setuptools
$ pip3 install six requests wheel pyyaml
# upgrade version 3.0.0 -> 3.13.0
$ pip3 install -U protobuf
# download the wheel
$ wget https://github.com/Qengineering/Paddle-Jetson-Nano/raw/main/paddlepaddle_gpu-2.0.0-cp36-cp36m-linux_aarch64.whl
# install Paddle
$ sudo -H pip3 install paddlepaddle_gpu-2.0.0-cp36-cp36m-linux_aarch64.whl
# clean up
$ rm paddlepaddle_gpu-2.0.0-cp36-cp36m-linux_aarch64.whl
```
## Wheels
Please find your **linux-aarch64** installation wheel here. The **cpXX** number refers to your Python3 version.<br/>

----

Please notice, this is the full Paddle package, not the Paddle Lite version for small devices and mobile phones.<br/>
For this guide of Paddle Lite see [Install Paddle Lite](https://qengineering.eu/install-paddle-on-jetson-nano.html) <br/>
