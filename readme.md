zabbix-server Role
=========

A role to install zabbix server and the databse.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-neoloc.zabbix-server-blue.svg)](https://galaxy.ansible.com/neoloc/ansible-role-zabbix-server/)


Requirements
------------

neoloc.zabbix-repo

Role Variables
--------------

```yaml
zabbix_server_configure: true
zabbix_server_database_name: zabbix
zabbix_server_database_user: zabbix
zabbix_server_database_password: zabbix
zabbix_server_database_host: localhost
```

Dependencies
------------

neoloc.zabbix-repo

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - neoloc.zabbix-repo
         - neoloc.zabbix-server

License
-------

See license.md

Author Information
------------------

[![Github](https://img.shields.io/badge/Github-neoloc-blue.svg)](https://github.com/neoloc)
