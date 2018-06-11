ansible-bootstrap
=========

A role to install Ansible pre-requisites in the target machine.

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

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
