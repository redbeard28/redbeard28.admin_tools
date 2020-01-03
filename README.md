# DEPRECATED !

## Please go to [ansible-role-basetools](https://github.com/redbeard28/ansible-role-basetools.git)


![Travis-ci](https://api.travis-ci.org/redbeard28/redbeard28.admin_tools.svg?branch=master&style=plastic)
![GitHub release](https://img.shields.io/github/release/redbeard28/redbeard28.admin-tools.svg?color=green&logo=github&style=plastic)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/redbeard28/redbeard28.admin_tools.svg?style=plastic)
![GitHub](https://img.shields.io/github/license/redbeard28/redbeard28.admin_tools.svg?style=plastic)

admin_tools
=========

A simple role to install those packages:
  * wget
  * curl
  * net-tools
  * ... more to come

Requirements
------------

Call this galaxy role  like this:

````bash
ansible-galaxy install -r requirements.yml 
````

Inside requirements.yml
````yaml
# from GitHub, overriding the name and specifying a specific tag
- src: https://github.com/GITHUB_USER/ansible-role-nginx
  version: master
  name: nginx_role
````

More info => [Ansible Docs](https://docs.ansible.com/ansible-container/roles/access.html)

Role Variables
--------------

NONE

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables that
are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: redbeard28.admin_tools, tags: install_tools }

License
-------

license GPLv3

Author Information
------------------

**Jérémie CUADRADO** - *redbeard28*

