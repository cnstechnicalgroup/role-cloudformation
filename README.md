Role: cns.cloudformation
========

Ansible role to deploy pre-configured CloudFormation web-centric stacks

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

In the current version, you can specify the following variables:

| Name               | Default |                                                              |
|--------------------|---------|--------------------------------------------------------------|
| admin_users        |   ---   | List containing all usernames to be created on target hosts. |


Install
-------

Add the following line to your `requirements.yml`:

```yml

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
