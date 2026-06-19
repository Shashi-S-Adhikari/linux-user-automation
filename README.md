# Linux User Automation using Ansible + ServiceNow

## Overview
Automates Linux user creation using ServiceNow requests and Ansible.

## Features
- Fetch request data from ServiceNow
- Create Linux user & group
- Verify user creation
- Update work notes
- Auto close RITM

## Tools
- Ansible
- ServiceNow API
- AWS EC2
- GitHub

## Run
```bash
ansible-playbook -i inventory/inventory.ini playbooks/create_user.yml

