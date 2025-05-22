lcbo database with signoz demo

```bash
ansible-playbook up.yml
```

This does docker compose up on an "empty" signoz in a codespace. Use this as a starting point for instrumenting your app.

```bash
ansible-playbook down.yml
```

This does docker compose down on the clickhouse-setup/docker-compose-minimal.yaml (the same docker-compose file from up.yml)
