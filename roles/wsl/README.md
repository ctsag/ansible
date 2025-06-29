Role Name
=========

Ubuntu WSL role

Requirements
------------

```
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

```
- hosts: localhost
  become: true
  roles:
      - wsl
```

License
-------

GPL-3.0-only

Author Information
------------------

Christos Tsagkournis
