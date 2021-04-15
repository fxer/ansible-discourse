## Setup Discourse via Ansible


## Local config
* macOS: `brew install ansible`
* CentOS/Amazon Linux: `yum install ansible`

## Examples
See what changes will be made:
* `ansible-playbook dev.yml -i environments/dev --diff --check`

Make those changes!:
* `ansible-playbook dev.yml -i environments/dev --diff`
