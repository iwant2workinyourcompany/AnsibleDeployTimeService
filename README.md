# AnsibleDeployTimeService

Playbooks allows install Docker app to the server & build and deploy app as a container

## Install Docker app:
```
ansible-playbook playbooks/docker.yml
```

## Pull& Build & Deploy:
```
ansible-playbook playbooks/deploy.yml
```

## Project structure:
```
├── ansible.cfg
├── hosts
├── playbooks
│   ├── deploy.yml
│   └── docker.yml
├── README.md
└── roles
    ├── deploy.docker/
    └── geerlingguy.docker/
```
