# Ansible Role: Aegir Cluster Node

[![Build Status](https://travis-ci.org/GetValkyrie/ansible-role-aegir-cluster-node.svg?branch=master)](https://travis-ci.org/GetValkyrie/ansible-role-aegir-cluster-node)

Configures an Aegir cluster node, a web server to host sites, and distribute
load across in high-performance and high-availability clusters.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):


## Dependencies


## Example Playbook

    - hosts: cluster-servers
      roles:
        - { role: getvalkyrie.aegir-cluster-node }

After the playbook runs, the server will be running a web server, and be ready
to have a master server deploy platforms and sites to it.

## License

MIT / BSD

## Author Information

This role was created in 2015 by [Christopher Gervais](http://ergonlogic.com/), lead maintainer of the [Aegir Hosting System](http://www.aegirproject.org).
