Role: cns.cloudformation
========

Ansible role to deploy pre-configured CloudFormation web-centric stacks

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

See task files for variables.

Install
-------

Add the following line to your `requirements.yml`:

```yml
- src: https://github.com/cnstechnicalgroup/role-cloudformation.git
  name: cns.cloudformation
```

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Sam Morrison

Examples
--------

```yaml
---
- name: common role test
  hosts: all
  roles:
    - cns.cloudformation
```
