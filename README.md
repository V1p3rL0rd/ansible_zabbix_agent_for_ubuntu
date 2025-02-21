# Ansible zabbix agent installer for ubuntu
This simple Ansible playbook automaticaly install and confiure zabbix agents on Ubuntu hosts.

The script is executed in several stages:

1) Download Zabbix repository package
2) Install Zabbix repository package
3) Update apt cache
4) Install Zabbix agent
5) Configure Zabbix agent
6) Ensure Zabbix agent is running and enabled
7) Restart Zabbix agent to apply configuration
