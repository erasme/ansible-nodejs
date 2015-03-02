nodejs Ansible playbook
=======================

[![Travis
CI](http://img.shields.io/travis/erasme/ansible-nodejs.svg?style=flat)](http://travis-ci.org/erasme/ansible-nodejs)
[![test-suite](http://img.shields.io/badge/ansible--roles--specs-ansible--nodejs-blue.svg?style=flat)](https://github.com/erasme/ansible-roles-specs/tree/master/ansible-nodejs/)
[![Ansible
Galaxy](http://img.shields.io/badge/galaxy-erasme.ruby--compiled-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2996)

This playbook will install nodejs from chris Lea PPA.

Requirements
------------

None

Role Variables
--------------

None

Tags
----

  - `nodejs` : applies to the whole role

Dependencies
------------

None

Example Playbook
----------------

This is mainly used as a dependency in your existing playbooks, like:

    dependencies:
      - { role: nodejs }

License
-------

MIT

Author Information
------------------

Created for @erasme by @leucos.

