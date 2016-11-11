# ansible_demo_project

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


## Author

* Pascal Stauffer
