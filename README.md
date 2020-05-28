[![](https://github.com/ansible-roles-matsumura/fortune/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/fortune/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/fortune/workflows/ansible-playbook/badge.svg)](https://github.com/ansible-roles-matsumura/fortune/actions?query=workflow%3Aansible-playbook)
[![](https://github.com/ansible-roles-matsumura/fortune/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/fortune/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-roles-matsumura/fortune/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/fortune/actions?query=workflow%3Ayamllint)

Role Description
=========

Installs [Fortune](http://www.thinkyhead.com/fortune) for CentOS7.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.repo-epel
    - fortune
```

License
-------

BSD
