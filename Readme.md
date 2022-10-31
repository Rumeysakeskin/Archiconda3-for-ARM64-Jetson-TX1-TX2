
`Archiconda3` is a distribution of conda for 64-bit ARM platform. 
Since Archiconda3 is tailored for ARM64 computer (Raspberry Pi, Jetson Devices-Jetson TX1/TX2), the setup process is different from the one with the normal Anaconda.
The aim of this repository is to create a conda environment on `aarch64`.

### Set up

#### Download the installation script and run:
- `$ wget https://github.com/Archiconda/build-tools/releases/download/0.2.3/Archiconda3-0.2.3-Linux-aarch64.sh`
- `$ bash Archiconda3-0.2.3-Linux-aarch64.sh` 


#### Activate installation:
- `$ source ~/.bashrc` 

#### Check the version, if conda is successfully installed, you will see the version info on the terminal:
- `$ conda --version` 

### How to use

#### Create conda environment:
- `$ conda create --name env_name` 

#### Create an environment with a specific version of Python:
- `$ conda create --name env_name python=3.7` 

#### Remove an environment:
- `$ conda env remove -n env_name` 

#### Activate the environment:
- `$ conda activate env_name` 

#### Deactivate the environment:
- `$ conda deactivate`

Reference: [How To Install Anaconda on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart)
