 ansible-playbooks

Contains playbooks to easily deploy applications.

Each directory contains different playbooks.

Every application directory contains a playbook <application_name>.yml. If you have Red Hat subscriptions, add your credentials to this playbook or create a vault of your own to save your credentials securely.

##### This playbook is mainly based on Gluster Deployment with Ansible
- ansible.cfg
  - Contains variable required for configuring anisble
  - Order in which ansible checks this file 
    - ANSIBLE_CONFIG (environment variable if set)
    - ansible.cfg (in the current directory)
    - ~/.ansible.cfg (in the home directory)
    - /etc/ansible/ansible.cfg

