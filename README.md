ntpd
====

Installs and enables the ntpd service.

Role Variables
--------------

 * ntpd_enabled: true

    Determines whether or not the ntpd service should be enabled and
    running.

Example Playbook
----------------

    - hosts: servers
      roles:
         - ntpd

License
-------

BSD

Author Information
------------------

Adam Herzog <adam@adamherzog.com>
