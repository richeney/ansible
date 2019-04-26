az
=========

Installs the latest version of the Azure CLI onto Ubuntu.

Reference: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest

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
     - { role: az }

License
-------

BSD

Author Information
------------------

Richard Cheney, Microsoft. Email: richard.cheney@microsoft.com 
