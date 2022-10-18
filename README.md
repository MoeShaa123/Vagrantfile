# Virtualisation

## Dev Env

### Vagrant

## Installation guide

- Ruby
- Vagrant
- VirtualBox

## Start VM

- update / check connectivity: `sudo apt-get update`
- upgrade: `sudo apt-get upgrade -y`
- current folder: `pwd`
- who am i: `uname or uname -a`
- folders at current location: `ls` or hidden files `ls -a`
- create file: `touch filename`
- create folder: `mkdir` foldername
- navigate to folder: `cd` foldername
- navigate out: `cd ..`
- navigate to home: `cd`
- remove file/folder: `rm -rf filename/foldername`
- copy test.ty into app folder
- How to navigate between OS & VM `exit` Enter
- for Admin acess `sudo` switch to admin user `sudo su`
- change permisson `chmod instruction file-name` i.e `chmod 700 test.text`
- Currently running process `top` & `ps aux`
- To remove any process `kill PID` - `kill 7`
- how to delete folder/hidden folder `ls -a`
- print last 3 lines from the test.txt `tail -n 3 test.txt`
- Research how to use `| pipe` & `grep` & `sort`
- pipe takes output of command and uses it for input
- grep searches for string/character in a file
- sort sorts filename by a key
- `ps aux` short list by name
- How to create/run a process in the background & foreground,
  create/run a process in both areas
- kill the process that you created
- Install `nginx` in our VM
- create a `private-network` between localhost & VM
- allocate an IP adress - for Mac users
- `sudo apt-get install nginx -y`
- How to check a tool/software status in linux
  `sudo systemctl status nginx -y`
