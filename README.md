andrewrothstein.nancy
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-nancy.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-nancy)

Installs [nancy](https://github.com/sonatype-nexus-community/nancy).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

> Note: If nancy_installer is toggled between Homebrew (brew) and tar.gz (tgz) mode, please make sure the executable is re-linked if you want to leverage the Homebrew version: `brew unlink nancy && brew link nancy`

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.nancy
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
