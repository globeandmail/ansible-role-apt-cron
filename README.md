ansible-role-apt-cron
======

Currently only Ubuntu is supported.

This role will install the 'unattended-upgrades' package, and will sync configs that you specify into /etc/apt/apt.conf.d/

Place your (static) configs in the directory pointed to by the ansible_role_apt_cron_d variable.


Variables
------

```
ansible_role_apt_cron_d: /path/to/group_files/apt-cron/*
```


Notes
------

https://help.ubuntu.com/lts/serverguide/automatic-updates.html
http://manpages.ubuntu.com/manpages/xenial/man8/unattended-upgrade.8.html
