rd-ansible-influx-db
=========

This role installs influxdb and optional kapacitor and allows you to specify a default user and password

Requirements
------------

This module requires Ansible 2.4

Role Variables
--------------

See defaults for variables and descriptions

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: rd-ansible-influx-db }
