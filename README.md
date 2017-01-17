# ansible_demo_project

[![Build Status](https://travis-ci.org/pstauffer/ansible_demo_project.svg?branch=master)](https://travis-ci.org/pstauffer/ansible_demo_project)

## Requirements
* Vagrant / VirtualBox
* Ansible

## Start Vagrant Box

```
# switch directory
cd vagrant

# start vagrant box
vagrant up

# connect to vagrant box
ssh -i id_rsa vagrant@172.1.1.101
ssh -i id_rsa vagrant@172.1.1.102
```

### Debugging

```
# check vagrant status
vagrant status
```


## Run playbook

```
ansible-playbook play-ntp.yml
```


## Useful Ansible Links
* [Ansible Docs](http://docs.ansible.com/ansible/intro.html)
* [List of all Modules](http://docs.ansible.com/ansible/list_of_all_modules.html)
* [ansible.cfg](https://raw.githubusercontent.com/ansible/ansible/devel/examples/ansible.cfg)
* [Best Practices](http://docs.ansible.com/ansible/playbooks_best_practices.html)


## Author

* Pascal Stauffer
