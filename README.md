# Integration Tests for Packet modules in Ansible

This repo contains playbooks which test and demonstrate usage of Packet modules in Ansible.

In order to run this. you need to
 - export PACKET_API_TOKEN as envvar
 - If the playbook needs project_id in vars, you need to set it to a project that you can access.
 - pip install packet-python >= 1.35
 - install Ansible >= 2.4

These playbooks create resources in the Packet host. Running it will cost you some Packet credit.

