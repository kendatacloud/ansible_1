# ansible_1

This is an awesome ansible guide to help you set it up and run! 

## Ansible and prerequisites
Ansible require python on all the machine to work
so we need it for running ansible itself and for the remote server

##1. Install python
For this purpose i am going to install python 3

run 'sudo apt update' first

...
sudo apt install python3-pip -y
...


##install ansible with pip

We only need to install ansible on the control machine, ansible
doesn't need to install on the remote server

so we goona use 'pip3' to install it

...
sudo pip3 install ansible
...

you can verify ansible installtion and python version by running
the command

...
ansible --version
...
