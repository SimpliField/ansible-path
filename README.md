Path
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
