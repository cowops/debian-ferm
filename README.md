Debian-Ferm
===========

ferm is a tool to maintain complex firewalls, without having the trouble to rewrite the complex rules over and over again.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-ferm }

Tasks
-----

  - Install [ferm](http://ferm.foo-projects.org/)

License
-------

BSD