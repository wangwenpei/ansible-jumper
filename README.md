Ansible-Jumper
==========================================================================================

Create or remove user on target machine by public keys.


Install
-------

```
ansible-galaxy install wangwenpei.jumper
```

Role Variables
--------------

```
pubkey_path: ./files/keys
pubkey_departing_path: ./files/departing-keys

```

How to
-----

- add member keys in your $pubkey_path



Example Playbook
----------------

For target machine

```
    - hosts: 127.0.0.1
      connection: local
      roles:
        - wangwenpei.jumper
```


License
-------

GPLv3

Author Information
------------------

Author: wangwenpei
