Lighthouse
=========

Lighthouse deploy role

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
| vars                     | description                              |
|--------------------------|------------------------------------------|
| lighthouse_dir           | Directory for Lighthouse static content  |
| lighthouse_nginx_config  | Nginx config path for Lighthouse server  |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lighthouse }

License
-------

MIT

Author Information
------------------

Aleksei Tasenko
