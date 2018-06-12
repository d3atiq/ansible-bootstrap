ansible-bootstrap
=========

A role to install Ansible pre-requisites in the target machine. This amounts to installing python-minimal on the target machine, which will enable it as an Ansible target. Use this role if your target machine doesn't contain a Python installation usable by Ansible.

Requirements
------------

Currently only supported for Ubuntu.

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------


    - hosts: servers
      gather_facts: false
      roles:
        - ansible-bootstrap

License
-------

MIT

Author Information
------------------

Under construction...
