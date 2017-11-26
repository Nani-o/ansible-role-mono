[![Build Status](https://travis-ci.org/Nani-o/ansible-role-mono.svg?branch=master)](https://travis-ci.org/Nani-o/ansible-role-mono)

mono
====

The only purpose of this role is to install Mono (the cross platform and open source .NET framework) on Linux hosts.

Requirements
------------

  - CentOS 6
  - CentOS 7
  - Ubuntu 12.04
  - Ubuntu 14.04
  - Ubuntu 16.04
  - Debian 7
  - Debian 8
  - Debian 9

Variables
---------

- mono_package

By default this variable is set to mono-devel. You can set it to whatever you like.

```YAML
mono_package: mono-complete
```

- mono_extra_packages

Set this variable if you want to add packages with mono-devel.

```YAML
mono_extra_packages:
  - ca-certificates-mono
  - mono-locale-extras
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mono }

License
-------

MIT

Author Information
------------------

Sofiane MEDJKOUNE
