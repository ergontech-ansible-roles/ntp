ntp Role
=========


Role Variables
--------------

```
ntp: true

ntp_timezone: 'America/Los_Angeles'

ntp_pools:
  - 0.us.pool.ntp.org
  - 1.us.pool.ntp.org
  - 2.us.pool.ntp.org
  - 3.us.pool.ntp.org

```

----------------

```
#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/ntp
#   version: master
#   name: ntp
```

License
-------

[MIT](LICENSE)