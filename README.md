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
