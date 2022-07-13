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