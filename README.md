# Installing-odoo-with-ansible
A playbook to install odoo from a management server using Ansible.

versions:
Ubuntu=18.04
Odoo=13

Steps of implementation on AWS:
1) create key pair
2) create security group
3) create your appropriate instance size and attach to the key pair
4) add the IP or dns to the inventory
5) from your management machine run this command:
```
ansible-playbook main.yml -i inventory
```
Note:please check the directories before doing the installation.
Note: you need to configure nginx manually, currently, we are working on it.
Note: The repo is under development!
