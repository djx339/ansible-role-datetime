Ansible Role: Datetime
=========

Correct the timezone and sync the time.

Requirements
------------

None.

Role Variables
--------------

`dt_timezone`: Timezone (default: Asia/Shanghai)

`dt_ntp_server`: The NTP server (default: 0.asia.pool.ntp.org)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  become: yes

  roles:
    - { role: djx339.datetime }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
