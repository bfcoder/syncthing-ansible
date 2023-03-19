# syncthing-ansible
Ansible playbook for setting up a syncthing VM


# Setup prerequisites

## Install Python/pip

## Install Ansible
```
pip install ansible
```

# Run

## Apply playbook with the following:
```
ansible-playbook -i inventory/all -v app.yml --ask-become-pass
```
