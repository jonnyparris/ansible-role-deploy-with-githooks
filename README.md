Role Name
=========

Ansible role to setup bare git repos with post receive hooks for a staging and live deployment. I.e. enable deployments with something like `git push live`.

Requirements
------------

n/a

Role Variables
--------------

`app_name`

Dependencies
------------

geerlingguy.git to ensure git is installed.

Example Playbook
----------------

TBC

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT
