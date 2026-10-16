# Week 5 Ansible Automation Project

**Author:** egregg  
**Target OS:** AlmaLinux  

## Project Overview
Automates software stack installation, web file deployment, service lifecycle, and post-reboot verification using modular Ansible roles.

## Directory Structure
- `inventory`: Host connection targets
- `main.yml`: Root playbook entrypoint
- `playbooks/roles/apache/`: Apache HTTPD configuration and sample HTML files (`index.html`, `about.html`, `contact.html`)
