# Linux Ansible Playbook

Really simple playbook for setting basic development environment
for the current user intended to be used with ansible-pull **after**
user creation, ssh and git setup.

To run locally:

```
$ ansible-playbook -K --connection=local local.yml
```

