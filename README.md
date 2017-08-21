andrewrothstein.ceph
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-ceph.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-ceph)

Installs the [Ceph](https://ceph.com/) binaries

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.ceph
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
