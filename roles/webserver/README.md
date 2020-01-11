Role Name
=========

Install 3 webservers.

Requirements
------------
provides 3 box: [webservers]
prdx-webserver136 192.168.43.20
prdx-webserver236 192.168.43.18
prdx-webserver336 192.168.43.16

Dependencies
------------
add this to the ansible host file usually on /etc/ansible/hosts
[webservers]
192.168.43.20
192.168.43.18
192.168.43.16

Playbook
----------------
ansible-playbook webserver.yml -b

License
-------
freely offer to u by team team3
