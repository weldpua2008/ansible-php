[![Build Status](https://travis-ci.org/weldpua2008/ansible-php.svg?branch=master)](https://travis-ci.org/weldpua2008/ansible-php)
[![Ansible Role](https://img.shields.io/ansible/role/5344.svg?style=plastic)](https://galaxy.ansible.com/list#/roles/5344)
[![Stories in Ready](https://badge.waffle.io/weldpua2008/ansible-apache-php.svg?label=ready&title=Ready)](http://waffle.io/weldpua2008/ansible-apache-php)

Role Name
========

Install php for different web servers:
 - apache
 - nginx
 
Requirements
------------

None

Role Variables
--------------

* `www_daemon` [default: `apache`]: apache, nginx
* `php_modules` - which php modules install

Dependencies
------------

None

Example Playbook
-------------------------

Only php:

    - hosts: servers
      roles:
         - { role: weldpua2008.ansible-php }


License
-------

MIT

Author Information
------------------

Valeriy Solovyov 