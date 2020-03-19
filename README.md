Ansible Role: couchdb
=========

Ansible role to install current couchdb on RHEL/CentOS

Requirements
------------

None.

Role Variables
--------------

The following variables must be set with values in a .yml file in either host_vars or group_vars:
```
couchdb_admin_secret
```

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cyberitas.ansible_role_couchdb }

License
-------

MIT

Author Information
------------------

Create in 2020 by Tom Emerson for Cyberitas Technologies, LLC
