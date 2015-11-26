Ansible Role for Webmin
=======================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-webmin.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-webmin)
 [![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-webmin.svg)](https://github.com/pantarei/ansible-role-webmin)
 [![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-webmin.svg)](https://github.com/pantarei/ansible-role-webmin/blob/master/LICENSE)
 [![Ansible Role](https://img.shields.io/ansible/role/6234.svg)](https://galaxy.ansible.com/detail#/role/6234)

Ansible Role for Webmin Installation.

Requirements
------------

This role require Ansible 1.9 or higher.

This role was designed for Ubuntu Server 14.04 LTS.

Role Variables
--------------

No additional role variables.

Dependencies
------------

-   [hswong3i.apt](https://galaxy.ansible.com/detail#/role/5970)

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: hswong3i.webmin }

License
-------

-   Code released under [MIT](https://github.com/hswong3i/ansible-role-webmin/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

