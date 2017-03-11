ansible-role-nginx
==================

Ansible role to install nginx.
Tested on Ubuntu Trusty and CentOS 7.
No usage of 'shell:', only ansible commands.

Requirements
------------
Role requires fact gathering enabled in the main playbook (`gather_facts: yes`).

Role Variables
--------------
None.

Dependencies
------------
None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: ansible-role-nginx

License
-------

BSD

Author Information
------------------

http://dev366.com
Igor Mikhaylov <igor@dev366.com>
