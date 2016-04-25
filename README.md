# ansible_openstack_create_vm

This project facilitates you creating a virtual machine (VM) instance in an Openstack cloud using Ansible.

Prerequisites:
--------------

- You are familiar with Openstack, e.g can create a keypair or an instance from the Horizon dashboard
- You are also familiar with Ansible e.g. you know how 'roles' can be defined 

Basic steps:
-------------
- Prepare your Openstack cloud, e.g. identify the network, image, flavor, keypair to be used for creating a VM
- Setup a Python virtual environment with Ansible >= 2.0
- Download the Openstack RC file and setup your shell environment variables
- Edit some VM/instance specific settings
- Run the ansible-play on play_create_vm.yaml 

Contact
--------

Faruque Sarker <writefaruq-at-gmail.com>