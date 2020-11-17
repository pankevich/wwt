Role Name
=========

Install and initialize postgresql server.

Requirements
------------

None.

Role Variables
--------------

OS-dependent postgresql_data_dir:

postgresql_data_dir: "/var/lib/pgsql/data"

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: postgres

License
-------

BSD

Author Information
------------------

Igor Pankevich, pankevich@gmail.com
