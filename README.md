[![Build Status](https://travis-ci.org/wtanaka/ansible-role-darktable.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-darktable)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-darktable.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-darktable)

wtanaka.darktable
=================

Ansible role to install darktable

Example Playbook
----------------

    - hosts: all
      roles:
        - { role: wtanaka.darktable }


### `darktable_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "darktable" is already in the
path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)


Author Information
------------------

https://wtanaka.com/
