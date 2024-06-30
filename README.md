# Windows Security Package Update

This Ansible playbook and role are designed to update a Windows security package MSI on target Windows servers.

## Requirements

- Ansible
- Windows servers with WinRM enabled


## Usage


To run only one role, you use the --tags option with ansible-playbook:

ansible-playbook -i inventory playbook.yml --tags "chocolatey"

ansible-playbook -i inventory playbook.yml --tags "url"
