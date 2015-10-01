consul
=========

Ansible role to 

- install and configure consul
- install and configure consul ui

on CentOS 7, CentOS 7 while being structured to allow easy branching for other distributions

Role Variables
--------------

See [defaults/main.yml], [vars/main.yml]

TODO: Describe any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: giabao.ansible-consul, consul_version: 0.5.0 }

License
-------

Apache license

Author Information
------------------

Tobias Gerschner

Gia Bao<giabao@sandinh.net> - http://sandinh.com
