cicd/ansible/roles/ansible_local/files is where installer.yml 
(from orion_installer repo and crafted as submodule)
drops the installer-inventory.txt file

Which can then be used as a role in packer provisioning and drop the installer-inventory.txt file onto the server image...

The installer-inventory.txt file is specifically listed in .gitignore so won't come through.
