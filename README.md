BARK: MYSQLEXPORT
=========

Automate a MySQL database backup

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**MYSQLEXPORT_DB_NAME**:

The name of the database to export.

**MYSQLEXPORT_DB_USER**:

The MySQL who will connect to the databse.

**MYSQLEXPORT_DB_USER_PASSWORD**

The password of the MySQL user.

**MYSQLEXPORT_DESTINATION_FOLDER**

Where to place the exported SQL file on the machine running Ansible.


Dependencies
------------

None known at the time, but only tested on Debian/Ubuntu machines.

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com 
