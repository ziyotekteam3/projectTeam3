Role Name
=========

A brief description of the role goes here.

Requirements
------------
provides 1 box [haproxy]
prdx-haproxy136 192.168.43.13
--------------

Description
------------
1- add this to the ansible host file usually on /etc/ansible/hosts
[haproxy]
192.168.43.13
2- modif file/ha.cfg files acording to the back and front end ip servers
------------

Calling the play
----------------
ansible-playbook haproxy.yml -b

---------------

License
-------
freely offer to u by team3

Author Information
------------------

