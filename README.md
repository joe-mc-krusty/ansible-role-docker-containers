Ansible Role: Docker Containers
=========
![Build Status](https://travis-ci.org/joe-mc-krusty/ansible-role-docker-containers.svg?branch=master)

![Ansible Role](https://img.shields.io/ansible/role/47281?label=galaxy)
![Ansible Role](https://img.shields.io/ansible/role/d/47281?label=galaxy%20downloads)


![GitHub stars](https://img.shields.io/github/stars/joe-mc-krusty/ansible-role-docker-containers?label=github)

An Ansible role for managing docker logins, images and containers on a server

Requirements
------------

This role assumes docker is already installed on the server. If it is not already the case, no worries, there are plenty of roles serving the purpose.  [geerlingguy.docker](https://galaxy.ansible.com/geerlingguy/docker) role will do a great job.

Check out the [docs](https://github.com/geerlingguy/ansible-role-docker/blob/master/README.md) to learn how to configure it.

Make sure the installation role is imported prior to this one.

Role Variables
--------------
docker_containers: []

Dependencies
------------
None

Example Playbook
----------------


License
-------
BSD

Author Information
------------------
This role was created by Xavier Sanna.
