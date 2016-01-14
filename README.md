Ansible Role for Webmin
=======================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-webmin.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-webmin)
 [![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-webmin.svg)](https://github.com/pantarei/ansible-role-webmin)
 [![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-webmin.svg)](https://github.com/pantarei/ansible-role-webmin/blob/master/LICENSE)
 [![Ansible Role](https://img.shields.io/ansible/role/6234.svg)](https://galaxy.ansible.com/detail#/role/6234)

Ansible Role for Webmin Installation.

Requirements
------------

This role require Ansible 2.0 or higher.

This role was designed for Ubuntu Server 14.04 LTS.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">parameter</th>
<th align="left">required</th>
<th align="left">default</th>
<th align="left">choices</th>
<th align="left">comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">webmin_listen</td>
<td align="left">yes</td>
<td align="left">10000</td>
<td align="left"></td>
<td align="left">Pass value as <code>listen</code> to <code>/etc/webmin/miniserv.conf</code>.</td>
</tr>
<tr class="even">
<td align="left">webmin_port</td>
<td align="left">yes</td>
<td align="left">10000</td>
<td align="left"></td>
<td align="left">Pass value as <code>port</code> to <code>/etc/webmin/miniserv.conf</code>.</td>
</tr>
<tr class="odd">
<td align="left">webmin_ssl</td>
<td align="left">yes</td>
<td align="left">1</td>
<td align="left"></td>
<td align="left">Pass value as <code>ssl</code> to <code>/etc/webmin/miniserv.conf</code>.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: hswong3i.webmin }

License
-------

-   Code released under [MIT](https://github.com/pantarei/ansible-role-webmin/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

