# Getting started

```bash
ansible-galaxy install -r requirements.yml

ansible-playbook site.yml
```

## Changing redis replicas

Edit `redis_server_replicas:` in `site.yml` and run:

```bash
ansible-playbook site.yml
```