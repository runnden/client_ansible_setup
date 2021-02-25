# client_ansible_setup
In the Roles directory is where all individual roles are kept for client setup


The plays directory is where the playbooks that call the individual roles. 

The master.yml is located in the plays directory. This playbook will call all of the installation roles except for NIS. 

NIS is called via the nis_install.yml playbook.
