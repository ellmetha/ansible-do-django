ansible-do-django
#################

This Ansible role allows to setup a Django project using some opiniated mechanisms and tools (eg.
regarding the way to use env-specific settings, etc). Django projects provisioned using this role
will be served using Nginx and uWSGI.

Requirements
============

* Ansible_ 2.0+
* Ubuntu/Debian-like targets
* Nginx
* PostgreSQL

License
=======

GPLv3. See ``LICENSE`` for more details.

.. _Ansible: https://www.ansible.com
