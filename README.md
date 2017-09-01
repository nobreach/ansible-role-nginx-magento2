Role Name
=========

Installs Nginx

Sets up Magento2 Virtual Host

Role Variables
--------------

server_name is what goes to Nginx server_name

Example Playbook
----------------

How to use role:

    - hosts: servers
      vars:
        - server_name: foo.com
      roles:
        - role: nobreach.nginx-magento2

License
-------

BSD
