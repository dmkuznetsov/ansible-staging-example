# Ansible playbook for personal staging based on docker

Read more: https://kuznetsov.dev/posts/staging/

### Requirements

Ubuntu 20.04

### How to start

1. Install Ansible
2. Copy `hosts/defaul.example.yml` to `hosts/default.yml` and update with your data
3. Copy `vars/default.example.yml` to `vars/default.yml` and update with your data
4. Run `ansible-playbook docker-staging-playbook.yml -i hosts/default.yml`