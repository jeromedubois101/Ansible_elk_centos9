# Install ELK on Centos 9 with Ansible

1) Copy the repo on Ansible Control node
2) Fill the inventory and vars
3) Prepare the vault file password at /home/automation/vault-password (default password is "jerome")
3) List hosts and checks : XXX
3) Execute the playbook : ansible-playbook playbook/playbook_elk.yml
    Assuming that pub key is deployed and user is sudo-nopassword
4) Paste the token from the cli and copy it to Kibana GUI
5) *systemctl status kibana* with privileges to gather code to insert into to GUI

Cluster is ready !
