# SUMMARY
The playbook in this example are about to complete the proper migration from 
non-prod mysql server to the local mysql8 server including rollback, preload
, common applications, mysql database and the basic tests beforehand. The changes 
mainly focus at the automation infrastructure for the mysql installation.

# REQUIRED
The playbook requires Ansible 2.x and Centos 7.5 in the remote servers.

The playbooks are meant to be a reference and starter's guide to install mysql 8 GA. 
The playbook was tested on CentOS 7.5 so I recommend that you use CentOS or RHEL 
to test these modules.

# SERVER
RHEL7.5 version reflects changes in Red Hat Enterprise Linux and CentOS 7.5:
1. Network device naming scheme has changed
2. iptables is replaced with firewalld
3. MySQL is replaced with MySQL8 GA

# RUN
command:
ansible-playbook -i hosts site.yml

