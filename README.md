Ansible Role: Docker Containers
=========
![Build Status](https://travis-ci.org/joe-mc-krusty/ansible-role-docker-containers.svg?branch=master)


An Ansible role managing docker logins, images and containers on a server

Requirements
------------

This role assumes docker is already installed on the server. If it is not already the case, I recommend using this excellent role [geerlingguy.docker](https://galaxy.ansible.com/geerlingguy/docker) to perform the installation.

Role Variables
--------------
docker_containers: []

Dependencies
------------
- geerlingguy.docker

Example Playbook
----------------


License
-------
BSD

Author Information
------------------
This role was created by Xavier Sanna
