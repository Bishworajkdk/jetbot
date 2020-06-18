# Jetbot
Install TensorFlow
Install the system package according to the requirements of TensorFlow:
sudo apt-get install libhdf5-serial-dev hdf5-tools libhdf5-dev zlib1g-dev zip libjpeg8-dev

Install and update PIP3
sudo apt-get install python3-pip
sudo pip3 install -U pip

Input this command to install Python package:
sudo pip3 install -U numpy grpcio absl-py py-cpuinfo psutil portpicker six mock requests gast h5py astor
termcolor protobuf keras-applications keras-preprocessing wrapt google-pasta setuptools testresources

Installation:
Because the firewall between the domestic network and the external network is isolated, the access
speed of the external network is relatively slow. Therefore, the first local installation method can be used
to complete the installation more stably and quickly.
sudo pip3 install --extra-index-url https://developer.download.nvidia.com/compute/redist/jp/v42
tensorflow-gpu == 1.13.1 + nv19.3
Then I installed Pytorch on it.
Since, we will be using resnet and alxenet for the image processing, so its .pth file need to be download.

Install Jupyter Lab
Use the following command to install the Jupyter Lab in order:
1) Installation dependencies:
sudo apt install nodejs npm

2) Install jupyterlab:
sudo pip3 install jupyter jupyterlab
sudo jupyter labextension install @jupyter-widgets/jupyterlab-manager
sudo jupyter labextension install @jupyterlab/statusbar

Generate the appropriate configuration file:
jupyter lab --generate-config

Set the password to enter the notebook:
jupyter notebook password
