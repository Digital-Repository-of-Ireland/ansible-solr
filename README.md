# ansible-solr
Ansible deployment of solr with hydra schema on Ubuntu 14.04

## Vagrant test :
*For Vagrant test environment, install Vagrant, Ansible and Virtualbox.*
*Vagrant uses "hostmanager" plugin. Before running, install with: `vagrant plugin install vagrant-hostmanager`.*

To spin up solr VM, run:

`vagrant up`

Solr service  will then be located at:

http://solr1.internal.tld:8080/solr

edit `inventory/group_vars/all.yml` to change software versions and passwords

