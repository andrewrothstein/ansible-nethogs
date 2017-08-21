andrewrothstein.nethogs
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-nethogs.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-nethogs)

Installs [NetHogs](https://github.com/raboof/nethogs)

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
    - andrewrothstein.nethogs
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
