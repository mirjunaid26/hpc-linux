# HPC and Linux Toolbox


## Useful Random Commands
### 1. To deactivate `auto_autoactivate_conda` which displays `(base)` infront of the username. 
```
conda config --set auto_activate_base False
source ~/.bashrc
```


### 2. ssh config file
#### What is an ssh config file?
An ssh config file is a text file that contains all of your ssh connection information. This includes the hostname of the server you’re connecting to, the username you’re using to connect, the port number, and the protocol you want to use. You can also specify a key file to use for authentication, as well as other options.
```
vi .ssh/config
```
