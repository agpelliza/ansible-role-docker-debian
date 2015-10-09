# Ansible Role: Docker Debian

An Ansible Role that installs Docker on Debian Linux servers.

## Requirements

None.

## Role Variables

None.

## Example Playbook

    - hosts: all
      remote_user: vagrant
      roles:
        - docker-debian
