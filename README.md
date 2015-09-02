# ansible
Ansible playbooks

# Description
Ansible playbooks that assist in deploying and configuring the servers.

# Example commands
```
ansible-playbook aws-linux-create.yml --extra-vars "access=$AWS_ACCESS_KEY secret=$AWS_SECRET_KEY key=$AWS_PEM subnet=$AWS_SUBNET name=$SERVER_NAME"
```

```
ansible-playbook sensu_install.yml --private-key=$LOCATION_OF_KEY_FILE
```
