configureHostname
=========
changes target hostname and replaces /etc/hosts


Role Variables
--------------

- hostnameVM : its value is the desired new hostname

Example Playbook
----------------

```
- hosts: X.X.X.X
  vars:
    - hostnameVM: <newHostname>
  roles:
    - configureHostname
```


Author Information
------------------

Yanis DILMI (UNIX-SAN)
