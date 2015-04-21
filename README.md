# Ansible-role-RatticWeb
Install RatticWeb for Ubuntu/Debian OS with ANSIBLE

This was tested with Ubuntu Trusty 14.04, you might need to adapt it slightly for other distro.

Rattic is a password management database designed for humans.

Requirements
------------
ANSIBLE pre installed localy and Ubuntu/Debian OS on the server where Rattic will be setup .


Executing the script:
----------------------
Edit the vars/main.yml file and customise it as needed.

    #  ansible-playbook -k RatticWeb-install.yml
    
