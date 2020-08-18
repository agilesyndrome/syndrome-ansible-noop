syndrome-ansible-noop
=========

This Ansible role does nothing. It's very useful when you need to have a galaxy.yml file, but that file has no requirements (empty) (More on this later)

Example galaxy.yml file
```
---
git+https://github.com/agilesyndrome/syndrome-ansible-noop
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: syndrome-ansible-noop }


Author: Drew Easley, AgileSyndrome