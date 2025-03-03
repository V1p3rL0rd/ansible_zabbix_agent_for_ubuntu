# Ansible zabbix agent installer for ubuntu
This is a very simple Ansible playbook will help you to install and confiure zabbix agents on Ubuntu hosts.

The playbook contains a several tasks:

1) Download Zabbix repository package
2) Install Zabbix repository package
3) Update apt cache
4) Install Zabbix agent
5) Configure Zabbix agent
6) Ensure Zabbix agent is running and enabled
7) Restart Zabbix agent to apply configuration
