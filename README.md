Building a simple LAMP stack and deploying Application using Ansible Playbooks.
-------------------------------------------

# SUMMARY
The changes in this example are about to complete the proper migration from 
non-prod mysql server to the local mysql8 server including rollback, preload
, common applications, mysql database and the basic tests. The changes mainly 
focus the automation infrastructure for the mysql installation.

# REQUIRED
These playbooks require Ansible 2.x and Centos 7.5 in the remote servers.

These playbooks are meant to be a reference and starter's guide to building
Ansible Playbooks. These playbooks were tested on CentOS 7.5 so I recommend
that you use CentOS or RHEL to test these modules.

# SERVER
RHEL7.5 version reflects changes in Red Hat Enterprise Linux and CentOS 7.5:
1. Network device naming scheme has changed
2. iptables is replaced with firewalld
3. MySQL is replaced with MySQL8

# RUN
command:
ansible-playbook -i hosts site.yml

