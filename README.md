[![Build Status](https://travis-ci.org/weldpua2008/ansible-php.svg?branch=master)](https://travis-ci.org/weldpua2008/ansible-php)

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