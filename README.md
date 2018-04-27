[![Build Status](https://travis-ci.org/ivtcro/otus_ansible_db_role.svg?branch=master)](https://travis-ci.org/ivtcro/otus_ansible_db_role)
otus_ansible_db_role
=========

Role for installing MongoDB

Role Variables
--------------

  mongo_port: MongoDB bind port
  mongo_bind_ip: MongoDB bind IP address
  env: environment name


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: all
  become: true
  vars:
    mongo_bind_ip: 0.0.0.0
  roles:
    - role: otus_ansible_db_role
```

License
-------

BSD

Author Information
------------------

Victor Vavulin (vvavulin@gmail.com)
