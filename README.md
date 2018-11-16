[![Build Status](https://travis-ci.org/jeffrey4l/ansible-alertmanager-role.svg?branch=master)](https://travis-ci.org/jeffrey4l/ansible-alertmanager-role)

Ansible alertmanager Role
=======================

A ansible role to install alertmanager server

Requirements
------------

* ansible >= 2.4

Role Variables
--------------

    alertmanager_bin_path: /opt/alertmanager
    alertmanager_etc_path: /etc/alertmanager
    alertmanager_data_path: /var/lib/alertmanager
    alertmanager_version: 0.15.3

Dependencies
------------

nothing

Example Playbook
----------------

    - name: Install alertmanager server
      hosts: all
      roles:
        - role: ansible-alertmanager-role

License
-------

GPLv3
