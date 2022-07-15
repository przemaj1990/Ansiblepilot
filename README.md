# Ansiblepilot
    Based on: https://www.ansiblepilot.com/

# Test host availability - Ansible module ping:
    ansible-playbook -i inventory 1_ping.yml 

# How to install Ansible in Ubuntu 20.04 - Ansible install
    #!/bin/bash
    sudo apt update
    sudo apt install ansible
    #!/bin/bash
    sudo apt update
    sudo apt install software-properties-common
    sudo add-apt-repository --yes --update ppa:ansible/ansible
    sudo apt remove ansible
    sudo apt install ansible-base

# Edit multi-line text - Ansible module blockinfile
    - ignore/practice

# Ansible troubleshooting - Indentation error
    - problem with tab or lack of it

# Print text or variable during execution - Ansible module debug
    - use -vv to print variable in verbose 
    ansible-playbook -i inventory -vv 5_print_variable.yml

# Install a package in RedHat-like systems - Ansible module yum
# Install a package in Debian-like systems - Ansible module apt
# Privilege escalation errors - Ansible troubleshooting 

# Checkout git repository via HTTPS - Ansible module git