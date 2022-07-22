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
# Rolling Update Debian-like systems - Ansible module apt
# Connection failed - Ansible troubleshooting
# Copy files from remote hosts - Remote to Local - Ansible module fetch
# Rolling Update RedHat like systems - Ansible module yum
    - problem with mirror on CentOS:
      solution:  https://techglimpse.com/failed-metadata-repo-appstream-centos-8/
      
# Edit single-line text -Ansible module lineinfile
# Test Windows host availability - Ansible module win_ping
# Create user account - Ansible module user
# Remove user account - Ansible module user
# Ansible troubleshooting - failure downloading
# Ansible troubleshooting - missing module parameter
# Extract an archive - Ansible module unarchive
# Open firewall ports in RedHat-like systems - Ansible module firewalld
# Change file permission - Ansible module file
# Delete file or directory - Ansible module file
# Download a file - Ansible module get_url
# Reboot remote hosts - Ansible module reboot
# Create an empty file - Ansible module file
# Checkout git repository via SSH - Ansible module git
# Ansible troubleshooting - Syntax Error
# Ansible troubleshooting - not a valid attribute for a Play error
# Ansible troubleshooting - fatal template error while templating string