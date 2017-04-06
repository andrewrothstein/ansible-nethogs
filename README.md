[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-nethogs.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-nethogs)
andrewrothstein.nethogs
=========

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
