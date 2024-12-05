# role-junos-software-upgrade
Ansible role to implement traffic drain or traffic return during software upgrade

# How to use
Step 1: Install the role in your environment.
   - You could have roles/requirements.yml if running on AAP.
     Project synch/source version control AAP job, which runs before the template job, will install the roles on the execution environment.
   - Or simple install on your environment.

Step 2: Define your variables

Step 3: Call the role from your playbook.

# Example use

## example vars file
- See example-vars.yml

## roles consumption
- See example-requirements.yml

## example playbook
- See example-playbook.yml
