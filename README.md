Ansible Role for GlusterFS Volume Management
============================================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-gluster-volume.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-gluster-volume)
[![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-gluster-volume.svg)](https://github.com/pantarei/ansible-role-gluster-volume)
[![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-gluster-volume.svg)](https://github.com/pantarei/ansible-role-gluster-volume/blob/master/LICENSE)

Ansible Role for GlusterFS Volume Management.

Requirements
------------

This role require Ansible 2.0 or higher.

This role was designed for Ubuntu Server 14.04 LTS and Ubuntu Server 16.04 LTS.

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
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>gluster_volume</td>
<td>yes</td>
<td><a href="https://github.com/pantarei/ansible-role-gluster-volume/blob/master/defaults/main.yml">defaults/main.yml</a></td>
<td></td>
<td>Pass list to <a href="http://docs.ansible.com/ansible/gluster_volume_module.html">gluster_volume module</a>, with additional `size` parameter for corresponding brick size.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: hswong3i.gluster_volume

License
-------

-   Code released under [MIT](https://github.com/pantarei/ansible-role-gluster-volume/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <a href="https://twitter.com/hswong3i" class="uri" class="uri">https://twitter.com/hswong3i</a>
    -   <a href="https://github.com/hswong3i" class="uri" class="uri">https://github.com/hswong3i</a>

