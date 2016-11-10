Path [![Build Status](https://travis-ci.org/SimpliField/ansible-path.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-path) [![Ansible Role](https://img.shields.io/ansible/role/10720.svg?maxAge=2592000)](https://galaxy.ansible.com/SimpliField/path/)
=========

Ansible role to create a path.
This role is designed to be call as dependency.

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
path: "/var/www"
owner: "www"
group: "www"
mode: 755
```

Dependencies
------------

There is no dependency.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: SimpliField.path
    path: "/var/www"
    owner: "www"
    group: "www"
```

License
-------

BSD
