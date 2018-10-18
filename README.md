# Elasticsearch rolling upgrades with Ansible

Usage:

```
ansible-playbook -K -i hosts elasticsearch-rolling-upgrade.yml
```

What you need to do:
- Provide your hosts file;
- Change the desired elasticsearch version in playbook;
