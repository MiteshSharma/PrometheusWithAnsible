# Prometheus Setup using Ansible

In this project, we are configurating prometheus with blackbox_exporter on one instance and node_exporter on another instance using ansible.

## Getting Started

Step 1: Update ip address of both instances in inventory file.

Step 2: Run ansible command to setup prometheus server with node exporter

Ansible command: ansible-playbook playbook.yml
