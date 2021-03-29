# haproxy-with-ansible
This repository includes an Ansible playbook that will configure Haproxy and dynamically add new hosts to the configuration as they come up in the Inventory

To use the playbook, 
1. Clone the repository in your workspace.
2. Update the hosts file to contain two new host groups [webservers] and [LoadBalancer]
3. Include relevant Ips in both the Host groups.
4. You must have the configuration file in ~/workspace folder.  
