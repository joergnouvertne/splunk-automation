# splunk-automation
Refactored playbook to automate splunk> administrative work

I started to use Ansible playbooks to automate certains splunk> related management tasks. 
This repository contains the refactored code using roles and is environment aware. 

To start with, I'll build the roles and playbooks to deploy a complete splunk> environment on 
a local workstation using Vagrant and Virtualbox. The next step is to take this playbook to deploy 
a complete environment in integration (workstation -> McK development) to enable testing of 
data onboarding, upgrades, changes in a real non-production environment. 
