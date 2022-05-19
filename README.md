up-and-running
=========

This is a role for my own use to set up my MicroOS box from a fresh installation.

Requirements
------------

Needs `community.general` collection, when running for a toolbox set the `toolbox_container` variable to true so it will run tasks only that are meant for a toolbox.

Example Playbook
----------------
```
---
 - name: setup box
   become: true
   hosts: localhost
   roles:
    - {role: up-and-running}
```

License
-------

Unlicense
