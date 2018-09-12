# Elasticsearch rolling upgrades with Ansible
Playbooks in Ansible.
Here are some real world examples we would like to share.

I use this playbook to upgrade elasticsearch from 6.2.2 to 6.4.0, you can customize your playbook based on this playbook.

Usage:

```
ansible-playbook -K -i hosts elasticsearch-rolling-upgrade.yml
```
