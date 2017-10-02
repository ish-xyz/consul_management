Consul Cluster Manager
=========

This Ansible role handle the first configuration and the scaling of a Consul Cluster (both client & server side).



Requirements
------------

The supported OS are:
	Centos 7
	RHEL 7

Required:
	NTPD configured
	Firewall configuration according with the consul documentations => http://consul.io/docs/install/index.html



Role Variables/Features
--------------

Use the settings in the default directory or override trough the variables in the invocating playbook.
This plabook can be used to create and scale a consul cluster.



Dependencies
------------
No other roles is needed for a standard installation and management.



Example Playbook
----------------

Example:

    - hosts: servers
      roles:
         - { role: consul_management }

====================================================================================

© 2017 - Present, Isham Araia. Consul Cluster Manager is released under an MIT-style license; see LICENSE for details.

BSD

Author Information
------------------
Isham Araia


