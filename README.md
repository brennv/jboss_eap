Ansible role: JBoss EAP
=========

A role to install JBoss Enterprise Application Platform on RHEL7. Intended to be used with [JBoss Middleware Playbooks](https://github.com/rhtconsulting/ansible-middleware-playbooks)

Requirements
------------

Ansible 1.8+
Access to JBOSS EAP downloads on [access.redhat.com](https://access.redhat.com)

Role Variables
--------------

This role supports different mechanisms for transferring the product zip files to the target host. These are documented in [the main playbooks README](https://github.com/rhtconsulting/ansible-middleware-playbooks), as the methods are supported across a variety of roles. See configurable [defaults](https://github.com/rhtconsulting/jboss_eap/blob/master/defaults/main.yml).

Dependencies
------------

- java
- unzip

Example Playbook
----------------
- [JBoss EAP 6.4 on CentOS 7](https://github.com/rhtconsulting/ansible-middleware-playbooks/blob/master/eap6.4-centos7.yml)
- [JBoss EAP 6.4 on RHEL 7](https://github.com/rhtconsulting/ansible-middleware-playbooks/blob/master/eap6.4-rhel7.yml)

License
-------

Apache

Author Information
------------------

* [Andrew Block] (https://github.com/sabre1041)
* [Albert Wong] (https://github.com/alberttwong)
* [Justin Holmes] (https://github.com/sherl0cks)
* [Kamesh Sampath] (https://github.com/kameshsampath)
