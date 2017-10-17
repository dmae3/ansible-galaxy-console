Console update role
=========

Console update ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* console_enviroment  
display server's enviroment.  
default is `local`

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - { role: redmage-console, console_enviroment: local }
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")
