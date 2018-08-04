# ansible-shibboleth-inventories
 This repository contains all inventories and all files needed by VMs that will built up with the playbook "ansible-shibboleth"

It has to be used with the "ansible-monitoring" repository to complete the "Ansible Playbook" that installs and configures a Shibboleth IdP v3.x

To get the Playbook working it is needed to run the commands below and change what you need under 'inventories' directory:

   * ```cd /opt/ ; git clone https://github.com/malavolti/ansible-shibboleth.git```
   * ```cd /opt/ansible-shibboleth ; git clone https://github.com/malavolti/ansible-shibboleth-inventories inventories```
