ansible
=========

Installs the Azure version of Ansible via pip, and then adds the dynamic inventory script.

Work in progress.  Needs testing.

References: 

* https://docs.microsoft.com/en-us/azure/virtual-machines/linux/ansible-install-configure
* https://docs.microsoft.com/en-us/azure/ansible/ansible-manage-azure-dynamic-inventories

Requirements
------------

All pre-reqs are installed by the role.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

- hosts: ubuntu
  remote_user: overlord
  become: true
  roles:
     - { role: ansible }

License
-------

BSD

Author Information
------------------

Richard Cheney, Microsoft. Email: richard.cheney@microsoft.com 
