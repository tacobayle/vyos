# vyos
## Prerequisites:
1. Make sure a VyOS router is reachable

## Input:
1. Make sure a valid config file is available

## Use the ansible playbook to:
1. Load the config file
2. Reboot the VyOS router

## Parameters:
All the paramaters/variables are stored in var/params.yml:

## Run the playbook:
ansible-playbook -i hostsBgpLocal vyos.yml

## Tests:
Playbooks have been tested against:
- vyos 3.13.11-1-586-vyos
- Ansible 2.8.0.dev0

## Improvement:s
