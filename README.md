Role Name
=========

Install Oracle Java JDK.

Role Variables
--------------

oracle_java_version: Choose which major java version to install.

Dependencies
------------

[geerlingguy.homebrew](https://github.com/geerlingguy/ansible-role-homebrew):
Used to ensure homebrew is installed. Install taps required for java.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - { role: username.rolename, oracle_java_version: 8 }
```

License
-------

MIT

Author Information
------------------

Julian Arevalo
