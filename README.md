# Borg backup  practice
This repository contains a simple `Ansible` playbook to setup test borg backup stand on the vagrant virtual machine from `Vagrantfile`
It makes backups every day at 7:40  a.m. and keeps 7 weekly and 6 monthly archives.

# Run  
0) `vagrant` and `Ansible` should be installed on your system
```
$ vagrant -v
Vagrant 2.2.5
$ ansible --version
ansible 2.9.1
...
```
1) Clone this repository
```bash  
$ git clone https://github.com/ligain/backup.git  
``` 
2) Go to project folder
```bash  
$ cd backup/
```  
3) Run `Vagrantfile`
```bash  
$ vagrant up
```


# Project Goals 
The code is written for educational purposes.