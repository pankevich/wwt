Role Name
=========

Set up haproxy server which load balances requests to servers
in group "apps".

Requirements
------------

None.

Role Variables
--------------

loadbalancer_port: "80"
haproxy_pkg: "haproxy"


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: haproxy_servers
      roles:
         - role: haproxy

License
-------

BSD

Author Information
------------------

Igor Pankevich, pankevich@gmail.com
