Ansible Role: AD ASREPRoasting.
=========

An Ansible role to enable ASREPRoasting attack on a number of users in the domain.

Requirements
------------

Needs to be run on the DC.

Role Variables
--------------

```yml
num_asreproastable_users: 1
```

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: pdc01
  roles:
    - role: xbufu.ad_asreproasting
      vars:
        num_asreproastable_users: 1
```

License
-------

MIT / BSD

Author Information
------------------

Created by xbufu.
