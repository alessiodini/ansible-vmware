# ansible-vmware
Ansible utilities for Vmware ESX

This repository contains playbooks for Vmware ESX operations:

- vm_rename.yaml: Playbook for renaming of a guest. The rename is done at Vmware inventory level. To let the rename be effective you must also make a storage vmotion. Why did non I planned a storage vmotion inside the playbook? Because @job I have several guests with TB of disks and tons of datastore, is better to analyze each scenario. You can play with the playbook and steal some code :) 
