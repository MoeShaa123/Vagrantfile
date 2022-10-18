# Virtualisation

## Dev Env

## Installation guide

- Ruby
- Vagrant
- VirtualBox

## Start VM using Vagrant

- update / check connectivity: `sudo apt-get update`
- upgrade: `sudo apt-get upgrade -y`

## Linux commands

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
- how to find folder/hidden folder `ls -a`
- print last 3 lines from the test.txt `tail -n 3 test.txt`
- Research how to use `| pipe` & `grep` & `sort`
- `| pipe` takes output of command and uses it for input
- `grep` searches for string/character in a file
- `sort` sorts filename by a key
- `ps aux` short list by name
- How to create/run a process in the background & foreground, create/run a process in both areas
- kill the process that you created

## Installing Nginx

- Install `nginx` in our VM
- create a `private-network` between localhost & VM
- allocate an IP adress - for Mac users
  `sudo apt-get install nginx -y`
- How to check a tool/software status in linux
  `sudo systemctl status nginx -y`
- `vagrant destroy` then `vagrant status`

## What is Virtualisation?

Virtualization relies on software to simulate hardware functionality and create a virtual computer system.

## What are its benefits?

- Slash your IT expenses
- Reduce downtime and enhance resiliency in disaster recovery situations
- Increase efficiency and productivity
- Control independence and DevOps
- Move to be more green-friendly

## What is Dev Env

- A development environment in software and web development is a workspace for developers to make changes without breaking anything in a live environment.
- An example of this is Visual Studio Code

## What is Vagrant?

- Vagrant is a tool for building and managing virtual machine environments in a single workflow

- Vagrant is designed for everyone as the easiest and fastest way to create a virtualized environment

## What is VirtualBox?

- VirtualBox is open-source software for virtualizing the x86 computing architecture
- It acts as a hypervisor, creating a VM (virtual machine) where the user can run another OS (operating system)

![diagram](https://user-images.githubusercontent.com/106158041/196493540-602a6738-f1a3-4765-a448-6134bf9fbb7b.jpg)



