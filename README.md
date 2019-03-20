[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-jenkins.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-jenkins)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Jenkins](https://jenkins.io/)
------------

Description
------------

 * [Ansible](https://www.ansible.com) for Jenkins

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
    vars_files:
    - vars/main.yml
  roles:
    - iac-ansible-jenkins
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
