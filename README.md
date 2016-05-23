freepbx13
===============

This role will instal freepbx 13.


Requirements
---------------------

Needs root/sudo

Role Varibles
-----------------

Nothing for now.

Example
---------------

    - hosts: freepbx
      user: root
      roles:
          - {role: eniac111.freepbx13}

Dependencies
-----------------

None

License
-------

2-clause BSD

Author Information
------------------

Blagovest Petrov
http://petrovs.info


Notice
------

Tested on Centos 7 running on LXC. Should work on older versions too.

TODO
----
* Support for Debian/Ubuntu
* Asterisk "make menuedit" settings to be configured by Ansible variables
