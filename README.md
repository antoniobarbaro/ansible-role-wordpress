Role Name
=========

Install Wordpress

Requirements
------------

None

Role Variables
--------------

- wordpress_version: "4.7.16"


Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      vars:
        wordpress_version: '4.7.17'    
      roles:
         - wordpress

License
-------

BSD

Author Information
------------------

Antonio Barbaro <antonio.barbaro@gmail.com>
