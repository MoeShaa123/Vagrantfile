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

<mxfile host="app.diagrams.net" modified="2022-10-18T16:41:58.462Z" agent="5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/106.0.0.0 Safari/537.36" etag="ZXEX1YTjWgzDr0dSJ_dy" version="20.4.1" type="device"><diagram id="IwGvefRJF4p4C2e_VPJM" name="Page-1">7Vltb5swEP41fEzFq4GPbdKt0latWqS9fJo8cMErwZlxEtJfPzs2AUxI+hKyVZlUqfh8Pt/d8/g4HMMZz8r3FM7TWxKjzLDNuDSciWHblmvbhvgz47WShMCRkoTiWMlqwRQ/IiU0lXSBY1S0FBkhGcPztjAieY4i1pJBSsmqrXZPsvauc5igjmAawawr/YpjlkppYPu1/AbhJK12tkAoZ2awUlaRFCmMyaohcq4NZ0wJYfJpVo5RJrJX5UWue9czu3WMopw9ZcFnPy/tT2gSrD5EOf0y/5HmDyNLxbGE2UJFrLxl6yoFKOYZUUNCWUoSksPsupZeUbLIYyT2Mfmo1vlIyJwLLS78hRhbK3jhghEuStksU7P3JGdq0hMmpA9i495glaggCxqhPRGqeBikCWL7MgG2mHA2IzJDjK75QooyyPCy7QhUrEq2enXi+YPK/TNwsDswfIEJhTxYHQ2GStZOHsxwkvPniOcGUS5YIsowp/ClmpjhOJY4oQI/wp8bUyLNc4JztgnFuzK8ibDFoSkkEMJ0wSh5QGOSEW53kpNcWLnHWaaJpF51QPoRFZ6hcj+mXQjUAqeqCaqWBGq4qs+lFSpZ2jiTvjkQaF4HtDtKlrjAPCm0eBvIDYCTDdo4OYHXAcoxTwlURZzm8cKULaBYeQujFOfojPFy2niBsHuwnJMeLFmLe/C6IuXbgOokRdH2vRZ4I8vrorc9kSdBz3b6X2YmzxN6G/ANABbwD77BtrCcBqruQeuAEy3octPbieShPL4UXbWAJoNFgaM2bu1O8KVtXTeBjQx5OxJUyZ7crKkd7gRZGodJ6zCAnnjZbapVzV5bN6SV1FGoGZLtaMcQzy1cN9QUmXsdtjSH3dDc65fltvWt4IB+sDuOmnPS45qBW8xeQcrgMClfx0NUYvZNzF14jq/G38XKCzMAajwp1eLNYN0Y3CGKeYyiLE2G+Fj5W+x3LXcnOZ7Nft2Qox+jHvYfjUDh0AT61wuZjoD70kLGDV20Gwygs+JIpUx32fNOUGqqMn2+TPG0N5VlhRXgz+UK8DRT9jBMAVafy8NyxTrMlTPqlTwNbf6R7RyHN74JBuFNAPY3O0E3or36PGCNiOAUJcv+T8MmDfVi8NKmxdNurYDnDlO9tJa6+lTo88s32/qufs1/oDqe5j3a/eQ3bJAxRagWO8HvBakmRvK7/JIrOGBebvhWzfOnRPyfTm8qW9w3aU7OdHh/LvcIvobxzqvwI92w8mH9G5XkS/1Tn3P9Bw==</diagram></mxfile>

