# games
various games written in python

# install developement evironment on windows

## install vscode

install extensions: python, git, jupyter
follow instructions here to install extra extention (remote developer tool)
https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-vscode

## install wsl (windows subsystem for linux)
Open your powershell and run:
```sh
wsl --install
```
Note: you need to restart the windows after run 

After reboot, type ```wsl``` to enter linux subsystem (it is ubuntu) and heck the version
with command
```sh
lsb_release -a 
```
update the related linux package with
```
sudo apt-get update
```
you windows home direction is under /mnt/c/Users/$USER

https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-vscode

git
https://learn.microsoft.com/zh-cn/windows/wsl/tutorials/wsl-git
