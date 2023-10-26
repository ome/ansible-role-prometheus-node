Prometheus
==========

[![Actions Status](https://github.com/ome/ansible-role-prometheus-node/workflows/Molecule/badge.svg)](https://github.com/ome/ansible-role-prometheus-node/actions)
[![Ansible Role](https://img.shields.io/badge/ansible--galaxy-prometheus_node-blue.svg)](https://galaxy.ansible.com/ui/standalone/roles/ome/prometheus_node/)

Prometheus node-exporter, defaults to listening on port 9100.


Role Variables
--------------

All variables are optional:
- `prometheus_node_version`: Prometheus Node version
- `prometheus_node_sha256`: SHA256 checksum for the Linux amd64 download
- `prometheus_node_args`: Arguments passed on the command line.
  See https://github.com/prometheus/node_exporter/ for configuration information.


Example playbook
----------------

    - hosts: localhost
      roles:
      - role: ome.prometheus_node


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
