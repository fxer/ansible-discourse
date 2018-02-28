## Setup Discourse via Ansible


## Local config
* `brew install ansible`

## Examples
See what changes will be made:
* `ansible-playbook dev.yml -i environments/dev --diff --check`

Make those changes!:
* `ansible-playbook dev.yml -i environments/dev --diff`
