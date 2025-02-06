Input Leap Role
=========

This role install LmStudio for Linux Ubuntu based and Mac systems

Requirements
------------

- Linux Ubuntu and Mint based system
- MacOS based system
- Ansible

Role Variables
--------------

defaults (current):
- appName: InputLeap

Dependencies
------------

NaN

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Build ByDefault.

Test
----

``ansible-playbook tests/test.yml -i tests/inventory --syntax-check``
