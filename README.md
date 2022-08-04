# Ansible_Role_for_setup_k8s_cluster
OS: Ubuntu-20.04

Step 1. Setup Ansible
Step 2. Install Roles
Step 3. update your ansible host files 
Step 4. Ping your instance to check connectivity
     ansible all -m ping # it will ask for yes/no then type 'yes'
Step 4. export MASTER_IP=<IP-of-Node> 
step 4. Run your Playbook
1. ansible-playbook play-roles.yaml
