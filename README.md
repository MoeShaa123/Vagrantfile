# Virtualisation

## Dev Env

## Installation guide

- Ruby
- Vagrant
- VirtualBox

## Start VM using Vagrant

- update / check connectivity: `sudo apt-get update`
- upgrade: `sudo apt-get upgrade -y`
- Remove the default - replace it with your own file
- restart - enable - `sudo nginx -t`
- `vagrant reload` or `vagrant destroy`

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

## Running logs

- remove the default `sudo /etc/nginx/sites-available/default`
- replace it with you own file ` sudo cp existing-location/etc/nginx/sites-available/default`
- restart `sudo sytemctl restart nginx`
- enable `sudo sytemctl restart nginx`

## Linux Env Variable

- syntax NAME=SHAHRUKH
- How to check existing env var `env`
- `export` to create env var

## MongoDB

- Create 2 VMs - 1.1 to set app in app machine - 1.2 install mongodb in db machine
- install required version of mongoDB with valid key
- ensure it's running - 3.1 change mongodb.conf file to allow access to everyone
- restart mongoDB and then enable then check status to ensure it's running with new config. `cat mongodb.conf`
- back to app machine to create env var called `export DB_HOST=mongodb/192.168.10.150:27017/posts`
- `sudo systemctl start mongod`
- change the mongod.conf
- ```net:
  port: 27017
  bindIp: 0.0.0.0
  ```
