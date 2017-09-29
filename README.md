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
	Firewall configuration according with the consul docs => http://consul.io/docs/install/index.html

Role Variables
--------------

Use the settings in the default directory or override trough the variables in the invocating playbook.

Dependencies
------------
No dependecies is needed.

Example Playbook
----------------

Example:

    - hosts: servers
      roles:
         - { role: consul_management }

=========================================================================== 
© 2017 - Present, Isham Araia. Consul Cluster Manager is released under an MIT-style license; see LICENSE for details.

BSD

Author Information
------------------
Isham Araia


