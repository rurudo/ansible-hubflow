#Ansible-hubflow

It does the following:

* Install Git for source
* Install github/hub command
* Install git-flow
* Add tab auto-completion for Git branches
* Display the current branch on prompt

#Installation

```
$ sudo apt-get install -y python-pip
$ sudo pip install ansible

$ git clone --recursive https://github.com/rurudo/ansible-hubflow
$ echo 'localhost ansible_connection=local' > hosts
$ ansible-playbook -i hosts ansible-hubflow/site.yml
```
