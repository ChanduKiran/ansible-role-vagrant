ansible-role-vagrant
====================
[![Build Status](https://travis-ci.org/vaulttec/ansible-role-vagrant.svg?branch=master)](https://travis-ci.org/vaulttec/ansible-role-vagrant)

Ansible role to install [Vagrant](https://www.vagrantup.com).


Requirements
------------

None


Role Variables
--------------

Available variables are listed below, along with default values:

```yaml
vagrant_version: 1.8.1
```


Dependencies
------------

None


Example Playbook
----------------

Install Vagrant version 1.8.1:

```yaml
- hosts: server
  roles:
     - vaulttec.vagrant
```

Install Vagrant version 1.8.0:

```yaml
- hosts: server
  roles:
     - { role: vaulttec.vagrant, vagrant_version: 1.8.0 }
```


Testing
-------

```bash
cd tests && vagrant up
```


License
-------

MIT
