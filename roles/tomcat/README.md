Role Name
=========

Set up tomcat by installing a hypothetical package name "tomcat".
Presumably, needful things like admin credentials, etc., are handled 
by the package's postinstall script.

Requirements
------------

None.

Role Variables
--------------

tomcat_pkg: tomcat
tomcat_port: 8080

Dependencies
------------

None

Example Playbook
----------------

    - hosts: app_servers
      roles:
         - role: tomcat

License
-------

BSD

Author Information
------------------

Igor Pankevich, pankevich@gmail.com
