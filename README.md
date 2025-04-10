# ansible

Ansible Configuration Files

## Control Node Setup

1. Setup Network Connection
2. Install Ansible `sudo dnf install ansible`

## Running Playbook with Become Password

```bash
ansible-playbook playbook.yaml --ask-become-pass
```

To make a check run, without performing changes use `--check` option.
